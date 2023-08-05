# HTTP-Post-for-NCC-VMS

HTTP Post SDK

{"AiEngine": <BR>
[{ <BR>
"created_at": <|YYYY|>-<|MM|>-<|DD|>T<|GMThh|>:<|mm|>:<|ss|>.000000Z, <BR>
  "camera_name": <|device_name|>,  <BR>
  "camera_mac": <|mac_address|>, <BR>
  "confidence": <|confidence|>, <BR>
  "label_name": <|name|>, <BR>
"class_id": <|class_id|>, <BR>
"x": <|left_x|>,  <BR>
"y": <|top_y|>, <BR>
"w": <|width|>, <BR>
"h": <|height|>, <BR>
"obj_tracking_id": <|obj_tracking_id|>,     		//Optional <BR>
"obj_dwell_time": <|obj_dwell_time|>,     		//Optional <BR>
"color_id": <|class_id|>,	       				//Optional <BR>
"behavior_id": <|behavior_name|>, <BR>
“rec_live”: <|rtsp_live|>, <BR>
“rec_play”: <|rtsp_playback|> <BR>
“base64_img”: <|base64_jpeg|>, <BR>
}], <BR>
}  <BR>
## Parameters
| Token | Description |
| ----- | ---------- |
| <%name%> | Name of the object |
| <%confidence%> | Confidence of the object |
| <%left_x%> | Bonding box of X |
| <%top_y%> | Bonding box of Y |
| <%width%> | Bonding box of width |
| <%height%> | Bonding box of height |
| <%center_x%> | Bonding box center X |
| <%center_y%> | Bonding box center Y |
| <%behavior_id%> | Behavior ID |
| <%color%> | Color of the object |
| <%linked_plate%> | Plate in the object |
| <%plate%> | Number plate |
| <%country%> | SA |
| <%logo%> | Car make |
| <%area%> | California, state name |
| <%full_image%> | Picture of the behavior |
| <%crop_image%> | Picture of the bounding box |
| <%pip_image%> | Picture of the behavior with bonding box |
| <%counter_count%> | Counting |
