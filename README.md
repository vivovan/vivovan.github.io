## How to Add a New Post

1. **Create a new file in the posts directory:** Navigate to the `_posts` directory in your project. This directory contains all the posts for your blog. Create a new file in this directory. The filename should be the slug of your post (the part that appears in the URL) and should end with `.md` or `.mdx` (for example, `my-first-post.md`).

2. **Add frontmatter to your post:** At the top of your new file, add a block of YAML between two lines of three dashes. This is called the frontmatter and it's where you define metadata about your post. Here's an example:

    ```markdown
    ---
    title: 'My First Post'
    date: '2022-01-01'
    ---
    ```

    Replace `'My First Post'` with the title of your post and `'2022-01-01'` with the date of your post.

3. **Write your post:** Below the frontmatter, you can start writing your post. You can use Markdown to format your text. Here's an example:

    ```markdown
    This is my first post!

    I'm very excited to start blogging.

    Here's a list of things I want to write about:

    - My projects
    - My learnings
    - My interests
    ```

4. **Save your post:** Once you're done writing, save your file. Your new post should now appear on your blog.

5. **Preview your post:** To preview your post, you can start your development server by running `npm run dev` (or `yarn dev` if you're using Yarn) in your terminal. Then, open your browser and navigate to `http://localhost:3000`. You should see your new post in the list of posts.

6. **Publish your post:** To publish your post, commit your changes and push them to your repository.