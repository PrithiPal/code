###Script for cache invalidation at Amazon CloudFront

Originally published: 2011-07-05 14:34:41
Last updated: 2011-07-05 14:40:58
Author: Andrey Nikishaev

This script scans directories that was uploaded to CloudFront and build files index. When you modify some files, script automatically see what files was modified since the last update, and clear cache on CloudFront only for them.