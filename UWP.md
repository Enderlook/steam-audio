Don't forget to download the Window SDK (10.0.10240.0 or later) and UWP tools from Visual Studio.

Also, use the Developer Command Console with admin mode for running commands.

Core
python get_dependencies.py -p uwp -t vs2022 --sharedcrt
python build.py --minimal -p uwp -t vs2022 --unity

Unity
python setup.py -p uwp -t vs2022
python build.py -p uwp -t vs2022

FMOD
python setup.py
python build.py -p uwp -t vs2022