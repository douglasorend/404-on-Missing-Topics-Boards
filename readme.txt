[hr]
[center][color=red][size=16pt][b]404 STATUS ON MISSING BOARDS/TOPICS v2.2[/b][/size][/color]
[url=http://www.simplemachines.org/community/index.php?action=profile;u=253913][b]By Dougiefresh[/b][/url] -> [url=http://custom.simplemachines.org/mods/index.php?mod=3969]Link to Mod[/url]
[/center]
[hr]

[color=blue][b][size=12pt][u]Install Requirements[/u][/size][/b][/color]
This mod was tested on SMF 2.0.9, but should work on SMF 2.1 Beta 1 thru 3, as well as SMF 2.0 and up. SMF 1.x is not and will not be supported.

[color=blue][b][size=12pt][u]Introduction[/u][/size][/b][/color]
This mod makes a minor change to the forum to return [url=http://en.wikipedia.org/wiki/List_of_HTTP_status_codes]HTML error codes[/url] when topics and boards are missing or inaccessible.

Per [url=http://www.simplemachines.org/community/index.php?action=profile;u=318771]Arantor[/url]'s [url=http://www.simplemachines.org/community/index.php?topic=530113.msg3763549#msg3763549]suggestion in his post[/url], error handling has been changed so that:
=> Board number too high returns 404 (Not Found)
=> Deleted boards return 410 (Gone)
=> Inaccessible boards return 403 (Forbidden)
=> Topic number too high returns 404 (Not Found)
=> Deleted topics return 410 (Gone)
=> Inaccessible topics return 403 (Forbidden)

By definition, a 404 error code (Not Found) is this:
[quote]The requested resource could not be found but may be available again in the future. Subsequent requests by the client are permissible.[/quote]
A 410 error code (Gone) is this:
[quote]Indicates that the resource requested is no longer available and will not be available again. This should be used when a resource has been intentionally removed and the resource should be purged. Upon receiving a 410 status code, the client should not request the resource again in the future. Clients such as search engines should remove the resource from their indices. [citation needed] Most use cases do not require clients and search engines to purge the resource, and a "404 Not Found" may be used instead.[/quote]
A 403 error code (Forbidden) is this:
[quote]The request was a valid request, but the server is refusing to respond to it. Unlike a 401 Unauthorized response, authenticating will make no difference. On servers where authentication is required, this commonly means that the provided credentials were successfully authenticated but that the credentials still do not grant the client permission to access the resource (e.g. a recognized user attempting to access restricted content).[/quote]

[color=blue][b][size=12pt][u]Admin Settings[/u][/size][/b][/color]
There are no admin settings.  To disable it, you must remove this mod.

[color=blue][b][size=12pt][u]Related Discussion[/u][/size][/b][/color]
o [url=http://www.simplemachines.org/community/index.php?topic=529649.0]Is there a way to disable specific URL[/url]

[color=blue][b][size=12pt][u]Other Information[/u][/size][/b][/color]
o [url=https://github.com/douglasorend/404_on_Missing_Topics_Boards]This mod at my GitHub repository[/url]
o [url=http://www.xptsp.com/board/free-modifications/404-on-missing-topics-boards/]This Mod at XPtsp.com[/url]
o [url=http://custom.simplemachines.org/mods/index.php?mod=3969]This mod on SMF's Customization Site[/url]

[color=blue][b][size=12pt][u]License[/u][/size][/b][/color]
Copyright (c) 2014 - 2018, Douglas Orend
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
