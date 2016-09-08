No one wants to write repetitive boilerplate code.

##Overview 
A collection of useful live templates especially if you use [AutoValue](https://github.com/google/auto/tree/master/value), [ButterKnife](https://github.com/JakeWharton/butterknife) or [Timber](https://github.com/JakeWharton/timber). Kotlin is also supported except enumerated annotations (pull requests are welcome).

###Android
**`idef`**: "Create enumerated annotation of Integer set"  
**`sdef`**: "Create enumerated annotation of String set"

###AutoValue
**`avtypeadapter`**:  "Create TypeAdapter for [AutoValueGson](https://github.com/rharter/auto-value-gson)"  
**`pa`**: "public abstract method"  
**`pai`**: "public abstract integer method"  
**`pas`**: "public abstract String method"

###ButterKnife
**`bbthis`**: "BindView annotated fields and methods in the specified Activity. The current content view is used as the view root."  
**`bbview`**: "BindView annotated fields and methods in the specified target using the source View as the view root."  
**`bfind`**: "Simpler version of View.findViewById(int) which infers the target type."  
**`bview`**: "Bind a field to the view for the specified ID. The view will automatically be cast to the field type."  
**`bviews`**: "Bind a field to the view for the specified ID. The view will automatically be cast to the field type."  
**`onclick`**: "Bind a method to an OnClickListener on the view for each ID specified."  
**`onclickview`**: "Bind a method to an OnClickListener on the view for each ID specified. Included View as a parameter."  
**`ontouch`**: "Bind a method to an OnTouchListener on the view for each ID specified."  
**`ontouchview`**: "Bind a method to an OnTouchListener on the view for each ID specified. Bind a method to an OnTouchListener on the view for each ID specified. Included View as a parameter."

###Timber
**`td`**: "Log a debug message with optional format args."  
**`te`**: "Log an error message with optional format args."  
**`ti`**: "Log an info message with optional format args."  
**`tv`**: "Log a verbose message with optional format args."  
**`tw`**: "Log a warning message with optional format args."  
**`twtf`**: "Log an assert message with optional format args."  
**`ttd`**: "Log a debug exception and a message with optional format args."  
**`tte`**: "Log an error exception and a message with optional format args."  
**`tti`**: "Log an info exception and a message with optional format args."  
**`ttv`**: "Log a verbose exception and a message with optional format args."  
**`ttw`**: "Log a warning exception and a message with optional format args."  
**`ttwtf`**: "Log an assert exception and a message with optional format args."

##Install
To get started, simply clone this repository to your Android Studio's config/templates folder.  
**1.** Live templates are stored in the following location:  
  - **OS X**: `~/Library/Preferences/AndroidStudio<VERSION>/templates`
  - **Linux**: `~AndroidStudio<VERSION>\config\templates`
  - **Windows**: `<USER_HOME_DIRECTORY>.AndroidStudio<VERSION>\config\templates`  

**2.** Once you found it, `cd` into it  
**3.** Run `git clone https://github.com/honza171/live-droids.git .`  
**4.** Restart AndroidStudio  

##TODO
- retrofit 2.0 methods   
- general improvements (better expressions, default parameters etc.)

##License

    Copyright 2016 Jan Jacko

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
