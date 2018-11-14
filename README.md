# Script that build box with packer 
Simple script that build box with packer 
 
## pre-requirements

- Install **Packer**
    - Download and install accordingly to your OS as described here : https://www.packer.io/downloads.html
	
## How to run the code
1. Open Command Line Interpreter: 

 OS system | Operation
 ------------ | -------------
| Windows | Start menu -> Run and type cmd |
| Linux  |Start terminal |
| macOS | Press Command - spacebar to launch Spotlight and type "Terminal," then double-click the search result. |

2. Run the following commands:
```
    git clone https://github.com/yaroslav-007/packer-nginx64.git
    cd packer-nginx64
    packer build nginx.json
```
