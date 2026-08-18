# AEON Portfolio + Pages CMS

This package converts the existing static AEON page into a Jekyll site whose Feed Posts, Projects, and Team Members are editable through Pages CMS.

## Install
1. Upload/commit every file and folder in this package to the root of the `AEON-Portfolio` GitHub repository.
2. In GitHub Pages, keep **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Go to https://app.pagescms.org and sign in with GitHub. Install the Pages CMS GitHub App for the `AEON-Portfolio` repository.
4. Open the repository in Pages CMS. You will see **Feed / News Posts**, **Projects**, and **Team Members**.
5. Create, edit, rename, or delete entries there. Images are stored in `assets/uploads`.
6. To let family members edit without GitHub accounts, invite them as Pages CMS collaborators by email from the CMS collaborator settings.

## Notes
- `.pages.yml` is the CMS configuration. Keep it in the repository root.
- `_config.yml` enables the Jekyll collections used by the homepage.
- `_posts` contains feed/blog posts.
- `_projects` contains project cards.
- `_members` contains team-member cards.
- The existing customer project-request form is kept in `index.html`.


## Team
Four starter team profiles are included. Their roles, bios, contact details, and photos can be edited or replaced from Pages CMS. The included images are placeholder initial avatars.
