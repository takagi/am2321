# Am2321

Measure temperature and humidity using Aosong's AM2321 sensor, including Munin plugin.

The default path of I2C character device is set to `/dev/i2c-1`, older Raspberry Pi may need it `/dev/i2c-0`.

    /* I2C character device */
    #define I2C_DEVICE "/dev/i2c-1"

## Author

* Masayuki Takagi (kamonama@gmail.com)

## Copyright

Copyright (c) 2014 Masayuki Takagi (kamonama@gmail.com)

## License

Licensed under the MIT License.
