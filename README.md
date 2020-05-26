## record
linux record tool, default 16k 16bit mono audio
depend library: libasound

## compile
gcc capture.c -lasound -Werror -o capture

## usage
./capture  
press `ctrl c` to stop the record

## API
`record_init()`
`record_deinit()`
`snd_pcm_readi()`

## license
MIT
