# Books grabber from tululu.org

> This app helps you to download science fiction books in bulk from [tululu.org](https://tululu.org/).

## Background

This app and README.md is created for educational purposes in the online courses for web developers [dvmn.org](https://dvmn.org/) and for DevOps engineers [rebrainme.com](https://rebrainme.com/)

## Usage

User can provide category's start and end page using optional arguments `--start_page` and `--end_page` respectively.  
For example, to download all category's books from pages 10 to 20, run:
```
python parse_tululu_category.py --start_page 10 --end_page 20
```
By default, `--start_page` is equal to `1`, `--end-page` is equal to the last page number of the desired category.  

For convenience, shortcuts `-s` instead of `--start_page` and `-e` instead of `--end_page` can be used:
```
python parse_tululu_category.py -s 5 -e 15
```

## API

**API is not implemented yet** 😓
![A picture to attract attention](https://zoolog.guru/wp-content/uploads/2019/09/94512.jpg)


## Install

In order to run it, you need Python 3.x and a few additional libs.  
To install these libs, simply use pip and requirements.txt:
```
pip install -r requirements.txt
```

## See Also

My other readme.md files that have been created a while ago:

1. https://github.com/esinmy/-sensive_blog
2. https://github.com/esinmy/django-orm-watching-storage
3. https://github.com/esinmy/correcting-grades

## License

MIT
