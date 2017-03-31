---
layout: post
title: You're up and running!
---

Next you can update your site name, avatar and other options using the _config.yml file in the root of your repository (shown below).

![_config.yml]({{ site.baseurl }}/images/config.png)

The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub.

# 我的博客

##### google翻墙设置


---
asdfasdfksalkf;lkdsaf;asfgkjlfdafsjashgkfdsal;nafdslanfksdfasdfk
就的撒看风景撒是否
s达芙妮爱空间的sa发
三卡士大夫
-  啊司法鉴定拉飞机啊
-  sdajflsadkfjj；lj
-  雷克萨点击




```
            String pathList = null;
            String systemPathList = System.getProperty("java.library.path", ".");
            String pathSep = System.getProperty("path.separator", ":");
            String fileSep = System.getProperty("file.separator", "/");
            
            
```

```

        @Override
	public String findLibrary(String libname) {
        String libFileName = System.mapLibraryName(libname);
        File libraryFile;
        boolean isNeedKillProcess = true;
    	if (mLibPaths != null && SHARE_LIBRARY_NAMES.contains(libFileName)) {
    		for (String libString : mLibPaths) {
    			libraryFile = new File(libString, libFileName);
    			if (libraryFile.exists()) {
    				isNeedKillProcess = true;
                    LOG.d("lib2 findLibrary path: " + libraryFile.getAbsolutePath());
    				return libraryFile.getAbsolutePath();
				}
			}
    		if(isNeedKillProcess){
    			Process.killProcess(Process.myPid());
    		}
    		return null;
		}else{
			return super.findLibrary(libname);
		}
    }

```





