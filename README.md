# qt-tute

[Qt](https://www.qt.io) tute

```
brew install qt
brew cask install qt-creator

vi ~/.zshrc
export PATH="/usr/local/opt/qt/bin:$PATH"
export LDFLAGS="-L/usr/local/opt/qt/lib $LDFLAGS"
export CPPFLAGS="-I/usr/local/opt/qt/include $CPPFLAGS"
export PKG_CONFIG_PATH="/usr/local/opt/qt/lib/pkgconfig"

which qmake
/usr/local/opt/qt/bin/qmake

which macdeployqt
/usr/local/opt/qt/bin/macdeployqt
```
