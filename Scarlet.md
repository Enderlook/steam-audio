Use the Developer Command Console with admin mode for running commands.

Core
python get_dependencies.py -p scarlet -t vs2022
python build.py --minimal -p scarlet -t vs2022 --unity -c release

Unity
python setup.py -p scarlet -t vs2022
python build.py -p scarlet -t vs2022 -c release

FMOD
python setup.py
python build.py -p scarlet -t vs2022 -c release