Abiquo API Jython client
========================

This project groups  a collection of examples of the Abiquo Cloud
Platform API, using Jython as a wrapper to the official Java client.


Building
---------

The only required step to build the Jython client is to configure
the classpath properly with all necessary dependencies. To do so,
you can just run:

    mvn compile

This will generate a *lib* directory with all needed dependencies and a
*CLASSPATH* file containing the CLASSPATH variable needed to run the Jython
client.

Once the classpath has been generated, you can run the Jython code by invoking
the wrapper script:

    sh wrapper.sh


Note on patches/pull requests
-----------------------------
 
 * Fork the project.
 * Make your feature addition or bug fix.
 * Add tests for it. This is important so I don't break it in a future version unintentionally.
 * Commit.
 * Send me a pull request. Bonus points for topic branches.


Issue Tracking
--------------

f you find any issue, please submit it to the [Bug tracking system](https://github.com/nacx/abijy/issues) and we
will do our best to fix it.


License
-------

This sowftare is licensed under the MIT license. See LICENSE file for details.

