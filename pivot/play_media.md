/*
Section: Pivot
Title: Playing Files
Language: en-US
*/

# Overview

It is pretty easy to play files, either hosted in your account or accessible via a URI.

# Play sample

The initial JSON to collect DTMF could look something like:

    <?php

    header('content-type:application/json');

    ?>

    {"module":"play"
     ,"data":{"id":"media_id"}
     ,"children":{
         "_":{
             "module":"play"
             ,"data":{"id":"http://some.file.server/some/file.mp3"}
             ,"children":{}
         }
     }
    }

Here we see two play actions, one that uses a media file hosted in your account and one that fetches the file from an HTTP server.
