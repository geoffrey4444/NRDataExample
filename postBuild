# This script installs the nano text editor
mkdir .temp
pushd .temp
wget https://www.nano-editor.org/dist/v2.9/nano-2.9.8.tar.xz
tar -xf nano-2.9.8.tar.xz
cd nano-2.9.8
./configure --prefix=$HOME/.local
make
make install
popd
echo "Nano installed successfully."
