# iOS-Helper

## URL
NSURL *originalURL = [NSURL URLWithString:@"http://hello.com/news"];
NSLog(@"%@", [originalURL URLByAppendingPathComponent:@"local"]);
NSLog(@"%@", [originalURL URLByAppendingPathExtension:@"local"]);

Output:
http://hello.com/news/local
http://hello.com/news.local
