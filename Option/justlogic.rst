

Just Logic
+++++++++++

**This Code C# Sample:**

.. code-block:: csharp

    public class Helper
     {
        public static string GetHash(string input)
        {
            HashAlgorithm hashAlgorithm = new SHA256CryptoServiceProvider();
       
            byte[] byteValue = System.Text.Encoding.UTF8.GetBytes(input);

            byte[] byteHash = hashAlgorithm.ComputeHash(byteValue);

            return Convert.ToBase64String(byteHash);
        }
    }


Key Goals
======================
.. image:: ./download.png


Options
=======

CodeMaster
----------

Robot Turtles
-------------

Primo / Cubetto
----------------