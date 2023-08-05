# HTTP-Post-for-NCC-VMS

## HTTP Post SDK for a Client Posting to LILIN Navigator Control Center VMS <BR>

{"AiEngine": <BR>
[{ <BR>
"created_at": "<|YYYY|>-<|MM|>-<|DD|>T<|GMThh|>:<|mm|>:<|ss|>.000000Z", <BR>
"camera_name": <|device_name|>,  <BR>
"camera_mac": <|mac_address|>, <BR>
  "confidence": <|confidence|>, <BR>
  "label_name": <|name|>, <BR>
"class_id": <|class_id|>, <BR>
"x": <|left_x|>,  <BR>
"y": <|top_y|>, <BR>
"w": <|width|>, <BR>
"h": <|height|>, <BR>
"obj_tracking_id": <|obj_tracking_id|>,     	//Optional <BR>
"obj_dwell_time": <|obj_dwell_time|>,     		//Optional <BR>
"color_id": <|class_id|>,	                    //Optional <BR>
"behavior_id": <|behavior_name|>, <BR>
“rec_live”: <|rtsp_live|>,                    //Optional <BR>
“rec_play”: <|rtsp_playback|> <BR>            //Optional <BR>
“base64_img”: <|base64_jpeg|>, <BR>
}], <BR>
}  <BR>
## Parameters
| Token | Description |
| ----- | ---------- |
| <%name%> | Name of the object |
| <%|mac_address%> | The mac address of your device | 
| <%confidence%> | Confidence of the object |
| <%left_x%> | Bonding box of X |
| <%top_y%> | Bonding box of Y |
| <%width%> | Bonding box of width |
| <%height%> | Bonding box of height |
| <%behavior_id%> | Behavior ID |
| <%color ID%> | Color of the object |
| <%color%> | Color of the object |
| <%rtsp_live%> | The live URL of your device | 
| <%rtsp_playback%> | The recording URL of your device | 
| <%base64_img%> | Base 64 encryption of the JPEG |

