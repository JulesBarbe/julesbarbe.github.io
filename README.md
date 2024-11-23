# website
personal website. made w hugo and hugo-coder theme.

# tasks:
1. deploy -> done
2. change theme -> done
3. add content
    - links -> done
    - nav (about, projects, blog, contact)
    - first blog post


# adding content
run `hugo new content {content_url}`. this will create a file with the given name in the content directory (draft as default). add markdown after the header. run hugo server -D to build with drafts. change draft to false to publish on deploy.

example command: 

` hugo new content content/posts/my-first-post.md`
