# animationrar
animation work
body{
	padding: 0px auto;
	margin: 0px;

}

.demo{
	width: 150px;
	height: 150px;
	margin:left;
	background: red;
	position: absolute;
	animation-name: change_bg;
	animation-duration: 10s;
	border-radius: 50%;

}

@keyframes change_color{
	from{
	backround-color:red;
}
to {
	background-color:yellow;

  }
}
@keyframes change_bg{
	0%{
		background: red;
		top: 0px;
		left: 0px;
	}

25%{
	background: yellow;
	top:0px;
	left: 500px;
	
}

50%{
background: green;
	top: 500px;
	left: 500px;
}
75%{
background: blue;
top: 500px;
left: 0px;
	
}

100%{
	background: purple;
	top: 0px;
	left: 0px;
}
}
}
