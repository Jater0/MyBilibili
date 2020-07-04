```
this is a east bilibili project
copy by wechat miniprogram
author: jater
date: 2020/7/2
create by: 微信开发者工具 stable v1.03
app version: 1.0.0
    '''
    style demo
    '''
    pages description:
        0.Components.MyTitle
            => this is a public header font-end
        1.home.page
            => MyTitle => public header
            => home page navigation
            => swiper
            => video lists
        2.video.page
            => MyTitle => public header
            => Video info
                => video link
                => video title
                => video detail
                    => author
                    => play count
                    => comment count
                    => date
                => video recommendation
                    => recommendation video list
                        => title
                        => play count
                        => comment count
                => video comment
                    => comment lists
                        => comment->user
                            => user head icon
                        => comment info
                            => username
                            => comment date
                        => comment content
    '''
```
[DirDescription]
  [Root]
    [---components]                 [PublicResource]
        ---MyTitle                      [PublicHeader]
    [---icon]                       [IconImage]
    [---pages]                      [style]
        ---index                        [HomePage]
        ---detail                       [VideoDetail]
    [---styles]                     [PublicStyle]
        ---fontawesome.wxss             [OutsizeStyle]
    [---utils]                      [utils]
        ---utils.js                     [utils.js]
    [---app.js]                     
    [---app.json]
    [---app.wxss]
    [---project.config.json]
    [---sitemap.json]