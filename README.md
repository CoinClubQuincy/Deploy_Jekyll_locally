# Deploy Jekyll ENV

deploy scripts for Jekyll



# Mac

***Manual Setup***

Before you can use Jekyll to test a site, you must:

-   Install  [Jekyll](https://jekyllrb.com/docs/installation/).
-   Create a Jekyll site. For more information, see "[Creating a GitHub Pages site with Jekyll](https://docs.github.com/en/articles/creating-a-github-pages-site-with-jekyll)."

We recommend using  [Bundler](http://bundler.io/)  to install and run Jekyll. Bundler manages Ruby gem dependencies, reduces Jekyll build errors, and prevents environment-related bugs. To install Bundler:

1.  Install Ruby. For more information, see "[Installing Ruby](https://www.ruby-lang.org/en/documentation/installation/)" in the Ruby documentation.
2.  Install Bundler. For more information, see "[Bundler](https://bundler.io/)."
## [](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll#building-your-site-locally)Building your site locally

3.  Open  Terminal.
4.  Navigate to the publishing source for your site. For more information, see "[Configuring a publishing source for your GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)."
5.  Run  `bundle install`.
6.  Run your Jekyll site locally 
``shellbundle exec jekyll serve
``

***Run Setup Script***
`````shell 
bash macSetup.sh
`````
If set up script has been run before Run Build Command
`````shell 
bundle exec jekyll serve
`````

# Ubuntu
***Manual Setup for different types of  linux build***

Before you can use Jekyll to test a site, you must:

-   Install  [Jekyll](https://jekyllrb.com/docs/installation/).
-   Create a Jekyll site. For more information, see "[Creating a GitHub Pages site with Jekyll](https://docs.github.com/en/articles/creating-a-github-pages-site-with-jekyll)."

We recommend using  [Bundler](http://bundler.io/)  to install and run Jekyll. Bundler manages Ruby gem dependencies, reduces Jekyll build errors, and prevents environment-related bugs. To install Bundler:

1.  Install Ruby. For more information, see "[Installing Ruby](https://www.ruby-lang.org/en/documentation/installation/)" in the Ruby documentation.
2.  Install Bundler. For more information, see "[Bundler](https://bundler.io/)."

## [](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll#building-your-site-locally)Building your site locally

1.  Open  Terminal.
2.  Navigate to the publishing source for your site. For more information, see "[Configuring a publishing source for your GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)."
3.  Run  `bundle install`.
4.  Run your Jekyll site locally.

***Run Setup Script***
`````shell 
UbuntuSetup.sh
`````
If set up script has been run before Run Build Command
`````shell 
bundle exec jekyll serve
`````

# Windows

***Manual Setup***

Before you can use Jekyll to test a site, you must:

-   Install  [Jekyll](https://jekyllrb.com/docs/installation/).
-   Create a Jekyll site. For more information, see "[Creating a GitHub Pages site with Jekyll](https://docs.github.com/en/articles/creating-a-github-pages-site-with-jekyll)."

We recommend using  [Bundler](http://bundler.io/)  to install and run Jekyll. Bundler manages Ruby gem dependencies, reduces Jekyll build errors, and prevents environment-related bugs. To install Bundler:

1.  Install Ruby. For more information, see "[Installing Ruby](https://www.ruby-lang.org/en/documentation/installation/)" in the Ruby documentation.
2.  Install Bundler. For more information, see "[Bundler](https://bundler.io/)."

## [](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll#building-your-site-locally)Building your site locally

3.  Open  Git Bash.
4.  Navigate to the publishing source for your site. For more information, see "[Configuring a publishing source for your GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)."
5.  Run  `bundle install`.
6.  Run your Jekyll site locally.
    
    ```shell
    bundle exec jekyll serve
    ```

## Script
1.  Download and install a  **Ruby+Devkit**  version from  [RubyInstaller Downloads](https://rubyinstaller.org/downloads/). Use default options for installation.   
 2. Run the  `ridk install`  step on the last stage of the installation wizard. This is needed for installing gems with native extensions. You can find additional information regarding this in the  [RubyInstaller Documentation](https://github.com/oneclick/rubyinstaller2#using-the-installer-on-a-target-system). From the options choose  `MSYS2 and MINGW development tool chain`.

3.Download  Windows Package Manager tool  https://docs.microsoft.com/en-gb/learn/modules/explore-windows-package-manager-tool/?WT.mc_id=AZ-MVP-5004737
2. execute script
`````shell
windowsSetup.cmd
`````

3. if setup script has been run then you only need to run the execution command in the correct directory
`````shell
bundle exec jekyll serve
`````
