/* ============================================
 *   Sanskar Yadav — Embedded Systems Developer
 * ============================================ */

typedef struct {
    char*  name;
    char*  role;
    char** hardware;
    char** skills;
    char*  currently_learning;
    char*  contact;
} Developer;

Developer sanskar = {
    .name               = "Sanskar Yadav",
    .role               = "Embedded Systems & Firmware Developer",
    .hardware           = {"ESP32", "ESP8266", "Arduino", "TI MSP432"},
    .skills             = {"Embedded C/C++", "RTOS", "IoT", "Bare-Metal Programming"},
    .currently_learning = "RTOS & Low-Level C/C++ Optimization",
    .contact            = "yadavsanskar4455@gmail.com"
};
