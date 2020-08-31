# hackerrank
.rc-time-picker {
display: inline-block;
position: relative;
box-sizing: border-box;
}
.rc-time-picker * {
box-sizing: border-box;
}
.rc-time-picker-clear {
position: absolute;
right: 6px;
cursor: pointer;
overflow: hidden;
width: 20px;
height: 20px;
text-align: center;
line-height: 20px;
top: 3px;
margin: 0;
}
.rc-time-picker-clear-icon:after {
content: "x";
font-size: 12px;
font-style: normal;
color: #aaa;
display: inline-block;
line-height: 1;
height: 20px;
width: 20px;
transition: color 0.3s ease;
}
.rc-time-picker-clear-icon:hover:after {
color: #666;
}
.rc-time-picker-panel-input {
margin: 0;
padding: 0;
width: 100%;
cursor: auto;
line-height: 1.5;
outline: 0;
border: 1px solid transparent;
}
.rc-time-picker-panel-input-wrap {
box-sizing: border-box;
position: relative;
padding: 6px;
border-bottom: 1px solid #e9e9e9;
}
.rc-time-picker-panel-input-invalid {
border-color: red;
}
.rc-time-picker-panel {
z-index: 1070;
width: 170px;
position: absolute;
box-sizing: border-box;
}

.rc-time-picker-panel * {
box-sizing: border-box;
}
.rc-time-picker-panel-inner {
display: inline-block;
position: relative;
outline: none;
list-style: none;
font-size: 12px;
text-align: left;
background-color: #fff;
border-radius: 4px;
box-shadow: 0 1px 5px #ccc;
background-clip: padding-box;
border: 1px solid #ccc;
line-height: 1.5;
}
.rc-time-picker-panel-narrow {
max-width: 113px;
}
.rc-time-picker-input {
width: 100%;
position: relative;
display: inline-block;
padding: 4px 7px;
height: 28px;
cursor: text;
font-size: 12px;
line-height: 1.5;
color: #666;
background-color: #fff;
background-image: none;
border: 1px solid #d9d9d9;
border-radius: 4px;
transition: border 0.2s cubic-bezier(0.645, 0.045, 0.355, 1), background 0.2s cubic-bezier(0.645, 0.045, 0.355, 1),
box-shadow 0.2s cubic-bezier(0.645, 0.045, 0.355, 1);
}
.rc-time-picker-input[disabled] {
color: #ccc;
background: #f7f7f7;
cursor: not-allowed;
}
.rc-time-picker-panel-select {
float: left;
font-size: 12px;
border: 1px solid #e9e9e9;
border-width: 0 1px;
margin-left: -1px;
box-sizing: border-box;
width: 56px;
max-height: 144px;
overflow-y: auto;
position: relative;
}
.rc-time-picker-panel-select-active {
overflow-y: auto;
}
.rc-time-picker-panel-select:first-child {
border-left: 0;
margin-left: 0;
}

.rc-time-picker-panel-select:last-child {
border-right: 0;
}
.rc-time-picker-panel-select ul {
list-style: none;
box-sizing: border-box;
margin: 0;
padding: 0;
width: 100%;
}
.rc-time-picker-panel-select li {
list-style: none;
margin: 0;
padding: 0 0 0 16px;
width: 100%;
height: 24px;
line-height: 24px;
text-align: left;
cursor: pointer;
user-select: none;
}
.rc-time-picker-panel-select li:hover {
background: #edfaff;
}
li.rc-time-picker-panel-select-option-selected {
background: #f7f7f7;
font-weight: bold;
}
li.rc-time-picker-panel-select-option-disabled {
color: #ccc;
}
li.rc-time-picker-panel-select-option-disabled:hover {
background: transparent;
cursor: not-allowed;
}
