{
    "name": "86 Eighty-six",
    "description": "86 anime",
    "developer":
    {
        "name": "Minh"
    },
    "icons":
    {
        "512": "icon_512.png"
    },
    "manifest_version": 3,
    "mod":
    {
        "license": "license.txt",
        "payload":
        {
            "background_music":
            [
                "music/track_1.mp3",
                "music/track_2.mp3",
                "music/track_3.mp3",
                "music/track_4.mp3"
            ],
            "browser_sounds":
            {
                "CLICK":
                [
                    "sound/click.mp3"
                ],
                "FEATURE_SWITCH_OFF":
                [
                    "sound/feature_switch_off.mp3"
                ],
                "FEATURE_SWITCH_ON":
                [
                    "sound/feature_switch_on.mp3"
                ],
                "HOVER":
                [
                    "sound/hover.mp3"
                ],
                "HOVER_UP":
                [
                    "sound/hover.mp3"
                ],
                "IMPORTANT_CLICK":
                [
                    "sound/important_click.mp3"
                ],
                "LEVEL_UPGRADE":
                [
                    "sound/level_upgrade.mp3"
                ],
                "LIMITER_OFF":
                [
                    "sound/limiter_off.mp3"
                ],
                "LIMITER_ON":
                [
                    "sound/limiter_on.mp3"
                ],
                "SWITCH_TOGGLE":
                [
                    "sound/switch.mp3"
                ],
                "TAB_CLOSE":
                [
                    "sound/close_tab.mp3"
                ],
                "TAB_INSERT":
                [
                    "sound/new_tab.mp3"
                ],
                "TAB_SLASH":
                [
                    "sound/tab_slash.mp3"
                ]
            },
            "keyboard_sounds":
            {
                "TYPING_BACKSPACE":
                [
                    "keyboard/backspace.wav"
                ],
                "TYPING_ENTER":
                [
                    "keyboard/enter.wav"
                ],
                "TYPING_LETTER":
                [
                    "keyboard/letter_1.wav",
                    "keyboard/letter_2.wav",
                    "keyboard/letter_3.wav"
                ],
                "TYPING_SPACE":
                [
                    "keyboard/space.wav"
                ]
            },
            "page_styles":
            [
                {
                    "css":
                    [
                        "webmodding/opera.css"
                    ],
                    "matches":
                    [
                        "https://*.opera.com/*"
                    ]
                }
            ],
            "shaders":
            {
                "Matrix green":
                {
                    "path": "shader/matrix.txt"
                },
                "Wave":
                {
                    "animation":
                    {
                        "duration": 60,
                        "steps": 3600
                    },
                    "path": "shader/wave.txt"
                }
            },
            "theme":
            {
                "dark":
                {
                    "gx_accent":
                    {
                        "h": 85,
                        "s": 100,
                        "l": 72
                    },
                    "gx_secondary_base":
                    {
                        "h": 272,
                        "s": 64,
                        "l": 16
                    }
                },
                "light":
                {
                    "gx_accent":
                    {
                        "h": 112,
                        "s": 80,
                        "l": 44
                    },
                    "gx_secondary_base":
                    {
                        "h": 272,
                        "s": 32,
                        "l": 16
                    }
                }
            },
            "wallpaper":
            {
                "dark":
                {   
                    "image": "wallpaper/dark.png",
                    "text_color": "#FFFFFF",
                    "text_shadow": "#757575"
                },
                "light":
                {
                    "image": "wallpaper/video.webm",
                    "first_frame": "wallpaper/first_frame.jpeg",
                    "text_color": "#FFFFFF",
                    "text_shadow": "#0B000E"
                }
            }
        },
        "schema_version": 1
    },
    "version": "1.0"
}
