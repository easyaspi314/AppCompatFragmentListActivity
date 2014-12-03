android-support-listactivity
============================

ListActivity for the Support Library and AppCompat.
This simple library contains two classes: ActionBarListActivity and FragmentListActivity.
To use them, just import this library into Eclipse. 

###Usage:###

Without AppCompat:
```java
import android.support.v4.app.FragmentListActivity;
...
public class Foo extends FragmentListActivity {
```

With AppCompat:
```java
import android.support.v7.app.ActionBarListActivity;
...
public class Bar extends ActionBarListActivity {
```
Note: If you want to use `onContentChanged()` on this one, replace it with `onSupportContentChanged()`. This only applies to ActionBarListActivity (and ActionBarActivity).

####Notice:####

All of this code is from the Android Open Source Project. I used the following files:

[ListActivity.java](https://github.com/android/platform_frameworks_base/blob/android-4.3_r1/core/java/android/app/ListActivity.java)
```java
/*
* Copyright (C) 2006 The Android Open Source Project
*
* Licensed under the Apache License, Version 2.0 (the "License");
* you may not use this file except in compliance with the License.
* You may obtain a copy of the License at
*
* http://www.apache.org/licenses/LICENSE-2.0
*
* Unless required by applicable law or agreed to in writing, software
* distributed under the License is distributed on an "AS IS" BASIS,
* WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
* See the License for the specific language governing permissions and
* limitations under the License.
*/
```

[list_content.xml](https://github.com/android/platform_frameworks_base/blob/master/core/res/res/layout/list_content.xml)
```xml
<!--
/* Copyright 2010, The Android Open Source Project
**
** Licensed under the Apache License, Version 2.0 (the "License");
** you may not use this file except in compliance with the License.
** You may obtain a copy of the License at
**
** http://www.apache.org/licenses/LICENSE-2.0
**
** Unless required by applicable law or agreed to in writing, software
** distributed under the License is distributed on an "AS IS" BASIS,
** WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
** See the License for the specific language governing permissions and
** limitations under the License.
*/
-->
```
