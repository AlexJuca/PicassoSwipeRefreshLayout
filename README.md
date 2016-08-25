# PicassoSwipeToRefresh 

[ ![JitPack](https://img.shields.io/github/release/jd-alexander/likebutton.svg?label=jitpack) ](https://jitpack.io/#jd-alexander/likebutton)
[![Build Status](https://travis-ci.org/jd-alexander/LikeButton.svg)](https://travis-ci.org/jd-alexander/LikeButton)
[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg?style=flat-square)](https://www.apache.org/licenses/LICENSE-2.0.html)
[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-LikeButton-green.svg?style=true)](https://android-arsenal.com/details/1/3038)


PicassoSwipeToRefresh is a custom SwipeToRefreshLayout view with a brand new animation

![Icon animations](https://media.giphy.com/media/3oz8xrGoB8DCI6LZ6M/giphy.gif "Icon animations")

---

# Table of Contents

1. [Gradle Dependency](https://github.com/AlexJuca/PicassoSwipeRefreshLayout#gradle-dependency)
   1. [Repository](https://github.com/AlexJuca/PicassoSwipeRefreshLayout#repository)
   2. [Dependency](https://github.com/AlexJuca/PicassoSwipeRefreshLayout#dependency)
2. [Basic Usage](https://github.com/AlexJuca/PicassoSwipeRefreshLayout#basic-usage)
12. [Contribution](https://github.com/AlexJuca/PicassoSwipeRefreshLayout#contribution)
13. [License](https://github.com/AlexJuca/PicassoSwipeRefreshLayout#license)

   
---

# Gradle Dependency


#### Repository

Add this in your root `build.gradle` file (**not** your module `build.gradle` file):

```gradle
allprojects {
	repositories {
		...
		maven { url "https://jitpack.io" }
	}
}
```

#### Dependency

Add this to your module's `build.gradle` file:

```gradle
dependencies {
	...
	compile 'com.github.alexjuca:PicassoSwipeRefreshLayout:0.2.0'
	}
}
```

---

# Basic Usage

#### XML

To use this View in your layout simply copy and paste the xml below. This provides the PicassoSwipeToRefreshLayout. 

```xml
<com.bitfyr.picassoswiperefreshlayout.PicassoSwipeRefreshLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent">

</com.bitfyr.picassoswiperefreshlayout.PicassoSwipeRefreshLayout>
```


# Contribution


Please fork repository and contribute using pull requests.

Any contributions, large or small, major features, bug fixes, additional language translations, unit/integration tests are welcomed and appreciated but will be thoroughly reviewed and discussed.


# License

    Copyright 2016 Alexandre Juca <corextechnologies@gmail.com>

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

