# Simple logging wrapper for the ESP32

## Dependencies
- [ESP-IDF](https://github.com/espressif/esp-idf)

### Features
- Wrapper around the esp\_log functionality

### Example

```c
#include "log.h"

const static char * TAG = "main";

// in your main content
void main(){
	log_initialize(LOG_DEBUG);

	// log message
	log(INFO, TAG, "Hello World!");
}
```

