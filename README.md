# hello-world
 {
  "robot_routine": [
    {
      "routine_id": 0,
      "robot_order": {
        "routine_sequence": [
          "robot_movement",
          "robot_voice"
        ],
        "delay_time": 0
      },
      "robot_voice": {
        "text_msg": [ "[[rate 180]] Claro que no. Solo obsérvate a ti mismo, estás hablando con un robot.",
                      "[[rate 180]] No [[slnc 100]] para nada. Yo no estoy platicando con un robot."
                    ],
        "voice": "Carlos",
        "delay_time": 500
      },
      "robot_movement": {
        "movement": [ [],
                      []
                    ], 
        "delay_time": 0
      }
    }
  ],
  "dialogflow_information": {
    "intent": "Centurion_Intent_Loco",
    "page": "NA",
    "route_groups": "Centurion_Intent_Respuestas_Triviales",
    "flow": "Default Start Flow"
  }
}
