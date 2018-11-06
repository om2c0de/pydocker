<h1>Install pydocker on macOS:</h1>

**Install Homebrew and Homebrew Cask**<br>

<code>$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
</code>

**Install Docker**

<code>$ brew cask install docker</code>
<p>Then run docker server using your GUI application icon.</p>

**Verify Docker installation**

<code>$ docker --version</code><br>
<code>$ docker-compose --version</code>

**Build and run**

<code>$ git clone https://gitlab.com/om2c0de/pydocker.git</code><br>
<code>$ cd pydocker</code><br>
<code>$ docker-compose build --no-cache && docker-compose up</code>

**Open 127.0.0.1:8000 in your browser**