if [ -d $1 ]; then
echo 'error: dir exists'
exit

else
mkdir $1
cd $1
mkdir css js

echo -e "h1{color: red;}" > css/style.css

echo -e "var string = Hello World;\nalert(srting);" > js/main.js

echo -e "<!DOCTYPE html>\n<head>\n<title>Hello</title>\n<link rel="stylesheet" href="css/style.css">\n<script src="js/main.js"></script>\n</head>\n<body>\n<h1>Hi</h1>\n</body>" > index.html

echo 'success'
exit
fi
