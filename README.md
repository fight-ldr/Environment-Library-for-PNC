# Environment-Library-for-PNC

### Control

+ Eigen
  + 安装`ubuntu16.04`与`ROS Kinetic`时自带的即可使用

+ CppAd

  + 安装步骤

    > tar -xf CppAD.tar.gz
    >
    > cd CppAD
    >
    > mkdir -p build && cd build
    >
    > cmake ../
    >
    > sudo make
    >
    > sudo make install
  + ![Reference](https://github.com/coin-or/CppAD)

+ ![Ipopt](https://github.com/fight-ldr/ipopt_install)

### Planning

+ Benchmark

  + 安装步骤

    >tar -xf benchmark.zip
    >
    >cd benchmark
    >
    >mkdir -p build && cd build
    >
    >cmake ../
    >
    >sudo make
    >
    >sudo make install

+ Ceres

  + 安装步骤

    > tar -xf ceres-solver-1.14.0.tar.gz
    >
    > cd ceres-solver-1.14.0
    >
    > mkdir -p build && cd build
    >
    > cmake ../
    >
    > sudo make
    >
    > sudo make install
    
  + ![Reference](https://github.com/ceres-solver/ceres-solver)

+ Cassidi

  + 安装步骤

    > cd Casadi
    >
    > mkdir -p build && cd build
    >
    > cmake ../
    >
    > sudo make
    >
    > sudo make install

+ Snopt

  + 安装步骤

    > bash install_snopt.sh

+ Nlopt

  + 安装步骤

    > tar -xf nlopt-nlopt-2.4.1.zip
    >
    > cd nlopt-nlopt-2.4.1
    >
    > mkdir -p build && cd build
    >
    > cmake ../
    >
    > sudo make
    >
    > sudo make install

+ Osqp

  + 安装步骤

    > tar -xf osqp.tar.gz
    >
    > cd osqp
    >
    > mkdir -p build && cd build
    >
    > cmake ../
    >
    > sudo make
    >
    > sudo make install

+ Osqp-eigen

  + 安装步骤

    > tar -xf osqp-eigen.tar.gz
    >
    > cd osqp-eigen
    >
    > mkdir -p build && cd build
    >
    > cmake ../
    >
    > sudo make
    >
    > sudo make install
  + 安装`Osqp-eigen`前要安装`Osqp`