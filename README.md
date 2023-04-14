# GHORDE 
Ghorde is a stable horde client for guilded and aims to provide an experience similar to midjourney on discord. 100% free. 

## How to run locally
### The sane route
#### Mac/Win/Linux
1. Install Docker (Docker Compose Pre-Packaged on Win/Mac, Needs to be installed separately on Linux)
2. Clone this project `git clone https://github.com/ghorde/ghorde`
3. Update submodules/libs `git submodule init && git submodule update` , `git submodule init ; git submodule update` (for windows)
4. CD into the project with `cd ghorde`
5. Run project with `docker-compose up`
    - For users of linux distros using docker desktop can alternatively also use the command `docker compose up` in case of docker-compose ownership clash.
6. Profit.