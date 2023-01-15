clean:
		rm -fr dist

post:
		hugo new posts/${POST_TITLE}.md
		sed -i '/title/c\title:"${POST_TITLE}"' content/posts/${POST_NAME}.md

build:
		hugo > /dev/null 2>&1
