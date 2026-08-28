# I4UG website

A static, GitHub Pages-ready site for the Institute for Ultimate Good.

## Publish with GitHub Pages

1. Create a GitHub repository and upload these files.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then save.

GitHub will publish the site at the URL shown on that page.

## Connect i4ug.org

The repository includes a `CNAME` file for `i4ug.org`. After enabling GitHub Pages:

1. In **Settings → Pages**, confirm the custom domain is `i4ug.org` and enable **Enforce HTTPS** once it becomes available.
2. At your domain provider, create these four `A` records for the root (`@`):
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
3. Create a `CNAME` record for `www` pointing to `<your-github-username>.github.io`.

DNS and certificate setup can take a little while to propagate. GitHub's Pages settings will show when the domain is verified and ready.
