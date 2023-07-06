# How to use ffdcaenc 2.1.3 to convert WAV files to DTS on Windows
 
If you are looking for a fast and free way to convert multichannel WAV files to DTS format on Windows, you might want to try ffdcaenc 2.1.3. This is a fork of the open-source DTS encoder dcaenc, which has been modified to support 24 bit input files, multiple mono input files, and DVD-compatible bitrates and frame rates.
 
ffdcaenc 2.1.3 is a command-line utility that can be downloaded from [here](https://github.com/filler56789/ffdcaenc-2/releases). To use it, you need to have a WAV file (or multiple mono WAV files) with the correct channel order and sample rate. The supported channel configurations are: 1.0, 1.1, 2.0, 2.1, 3.0, 3.1, 4.0, 4.1, 5.0 and 5.1. The supported sample rates are: 44100 Hz, 48000 Hz and 96000 Hz.
 
**Download 🆓 [https://t.co/k9oKk6JF6P](https://t.co/k9oKk6JF6P)**


 
The basic syntax of ffdcaenc 2.1.3 is:
 `ffdcaenc -i input.wav -o output.dts -b bitrate` 
where input.wav is the name of the input WAV file (or the first mono WAV file if using multiple files), output.dts is the name of the output DTS file, and bitrate is the desired bitrate in kbps (from 64 to 1536).
 
If you are using multiple mono WAV files, you need to use the -m flag and specify the channel order with -0, -1, -2, etc. For example:
 `ffdcaenc -m -0 left.wav -1 right.wav -2 center.wav -3 lfe.wav -4 ls.wav -5 rs.wav -o output.dts -b bitrate` 
This will create a 5.1 DTS file from six mono WAV files.
 
ffdcaenc 2.1.3 also supports some optional flags that can be used to adjust the encoding parameters or enable some features. For example:
 
How to use ffdcaenc 2.1.3 Windows to convert wav files to DTS,  ffdcaenc 2.1.3 Windows download link,  ffdcaenc 2.1.3 Windows vs mulders-dtsenc,  ffdcaenc 2.1.3 Windows 24 bit input support,  ffdcaenc 2.1.3 Windows multiple mono input files,  ffdcaenc 2.1.3 Windows DVD frame rates,  ffdcaenc 2.1.3 Windows command line options,  ffdcaenc 2.1.3 Windows DTS CD and DVD flags,  ffdcaenc 2.1.3 Windows channel order for 5.1,  ffdcaenc 2.1.3 Windows progress indicator,  ffdcaenc 2.1.3 Windows Unicode file names support,  ffdcaenc 2.1.3 Windows Visual Studio project file,  ffdcaenc 2.1.3 Windows source code and configure script,  ffdcaenc 2.1.3 Windows license and patent issues,  ffdcaenc 2.1.3 Windows history and changelog,  ffdcaenc 2.1.3 Windows compatibility with AudioMuxer and Muxman,  ffdcaenc 2.1.3 Windows SPDIF or HDMI output,  ffdcaenc 2.1.3 Windows dtsenc fork and update,  ffdcaenc 2.1.3 Windows DTS Coherent Acoustics codec implementation,  ffdcaenc 2.1.3 Windows core part of the encoder,  ffdcaenc 2.1.3 Windows public specification ETSI TS 102 114 V1.2.1,  ffdcaenc 2.1.3 Windows DTS technology patents,  ffdcaenc 2.1.3 Windows project page and git repository,  ffdcaenc 2.1.3 Windows reviews and feedbacks,  ffdcaenc 2.1.3 Windows alternatives and comparisons,  How to install ffdcaenc 2.1.3 Windows on your PC,  How to uninstall ffdcaenc 2.1.3 Windows from your PC,  How to update ffdcaenc 2.1.3 Windows to the latest version,  How to troubleshoot ffdcaenc 2.1.3 Windows errors and issues,  How to optimize ffdcaenc 2.1.3 Windows performance and quality,  How to use ffdcaenc 2.1.3 Windows with other audio tools and software,  How to create DTS sound tracks for a DVD with ffdcaenc 2.1.3 Windows,  How to play DTS files created by ffdcaenc 2.1.3 Windows on a receiver or a player,  How to edit DTS files created by ffdcaenc 2.1.3 Windows with an audio editor,  How to convert DTS files created by ffdcaenc 2.1 .3 Windows to other audio formats,  How to batch convert multiple wav files to DTS with ffdcaenc 2 .13 .Windows ,  How to change the bitrate of DTS files created by ffdcaenc .21 .Windows ,  How to adjust the volume of DTS files created by .13 .Windows ,  How to normalize the loudness of DTS files created by .21 .Windows ,  How to add metadata and tags to DTS files created by .13 .Windows ,  How to split or merge DTS files created by .21 .Windows ,  How to extract audio from video files and convert them to DTS with .13 .Windows ,  How to record audio from microphone or other sources and convert them to DTS with .21 .Windows ,  How to test the quality of DTS files created by .13 .Windows ,  How to compare the quality of DTS files created by .21 .Windows with other encoders
 
- -r flag enables raw mode (no header or footer)
- -c flag enables CRC protection
- -d flag enables dialog normalization
- -f flag sets the output frame size (default is auto)
- -s flag sets the sample rate conversion quality (from 0 to 9)
- -v flag sets the verbosity level (from 0 to 3)
- -h flag displays the help message

For more details on how to use ffdcaenc 2.1.3, you can refer to the README.md file included in the download package or visit the [GitHub page](https://github.com/filler56789/ffdcaenc-2).
 
With ffdcaenc 2.1.3, you can easily create DTS files from your WAV files and enjoy them on your home theater system or DVD player.
  
## How to play DTS files on Windows
 
Once you have created your DTS files with ffdcaenc 2.1.3, you might want to play them on your Windows computer. However, not all media players support DTS format natively. You might need to install some codecs or plugins to enable DTS playback.
 
One of the most popular media players that can play DTS files is VLC Media Player. VLC is a free and open-source player that can handle almost any media format. To play DTS files with VLC, you just need to open the file with VLC and select the appropriate audio track. You can also adjust the audio settings in the Tools menu.
 
Another option is to use foobar2000, a lightweight and customizable audio player. foobar2000 can play DTS files with the help of a plugin called foo\_input\_dts. You can download the plugin from [here](https://www.foobar2000.org/components/view/foo_input_dts) and install it in your foobar2000 components folder. Then, you can open your DTS files with foobar2000 and enjoy them.
 
If you want to play your DTS files on a DVD player or a home theater system, you need to burn them to a CD or a DVD. You can use any CD/DVD burning software that supports DTS format, such as Nero Burning ROM, ImgBurn or CDBurnerXP. You need to create an audio CD or a DVD-Audio disc and add your DTS files as tracks. Make sure your CD/DVD burner supports the selected disc type and bitrate.
 
With these methods, you can play your DTS files on Windows or any other device that supports DTS format.
 8cf37b1e13
 
