# GHORDE 
Ghorde is a stable horde client for guilded and aims to provide an experience similar to midjourney on discord. 100% free. 

## How to run locally
### The sane route
#### Mac/Win/Linux
1. Install Docker (Docker Compose Pre-Packaged on Win/Mac, Needs to be installed separately on Linux)
2. Clone this project `git clone https://github.com/ghorde/ghorde`
3. CD into the project with `cd ghorde`
4. Update submodules/libs `git submodule init && git submodule update` , `git submodule init ; git submodule update` (for windows)
5. Run project with `docker-compose up`
    - For users of linux distros using docker desktop can alternatively also use the command `docker compose up` in case of docker-compose ownership clash.
6. Profit.

## Bot Setup
After performing a clean install of all the dependencies through the setups stated above, we move onto the bot setup.
- Switch onto the ghorde-api directory and refer to the .env.sample file and create you own .env file.
- Switch onto the ghorde-bot directory and to the .env.sample file and create your own .env file. This step does involve generating your own unique bot token from Guilded.
