# Markdown Image Helper

To handle the image problem when using Hexo, I found this project [Give asset image in hexo a absolutely path automatically](https://github.com/CodeFalling/hexo-asset-image), but i have to create the image directory and copy image to it. There should be an easier way to do this, [markdown-image-helper](https://github.com/bigyuki/markdown-image-helper) meet the demand, I just fork it and change a little thing:

- Create an directory using the article's name (not always named "assets")
- Paste the path of image to the the editor

[]()

## Install

### local Install

```shell
# 1 change to the atom packages directory
cd ~/.atom/packages/

# 2 clone to the local
git clone https://github.com/andylei77/markdown-image-helper.git

# 3 using apm install to local
cd markdown-image-helper
apm install
```


## Usage
1. Take a screenshot or copy any image to the clipboard.
2. Paste it into Atom markdown editor
3. See that an directory name "assets" was create, and the directory has a png file, and a url was inserted.

## Example
* Before

    ![before](https://github.com/bigyuki/markdown-image-helper/raw/master/assets/README-31bb2.png)

* After

    ![after](https://github.com/bigyuki/markdown-image-helper/raw/master/assets/README-d1eba.png)
