name	about	title	labels	assignees
Bug report (English)

Create a bug report to help us improve our content.

Your LeetCode thesudhir

Category of the bug
 Question : 85. Maximal Rectangle
 Solution : approach 3
 Language : Java
Description of the bug
Code you used for Submit/Run operation
.
.
.
.

            // update area
            for(int j = 0; j < n; j++) {
                maxarea = Math.max(maxarea, (right[j] - left[j]) * height[j]);
            }
        }
        return maxarea;
    }
    
    
Language used for code : Java
Expected behavior : Compilation should be fine.
Screenshots


There is a compilation issue with Java solution of approach 3 of mentioned problem. "}" is missing.

thanks
Sudhir Yadav
(thesudhir)
