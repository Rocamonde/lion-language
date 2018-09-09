------------------------------------------
The Lion Programming Language version 0.1a
==========================================

High level, idiomatic scripting language for agnostic telemetry programming 
on top of the Savannah Framework.

Lion's proposed main features:

  - Interpreted, not compiled
  - Simplicity and explicitness
  - Support for translated key words
  - Human language-like syntax, while trying to preserve powerful OOP features.
  - Support for Python extensions
  

## Context and purpose

Savannah is a copyrighted advanced data harvesting and monitoring framework written in Python. At first, it was thought to be strictly private, proprietary and closed-source. However, as it grew in capabilities, a need to provide ways to expand and customise Savannah's potential arose. These ways are materialised in Savannah's official open-source SDK, that will include a client-side Python library, an API for Savannah Cloud service and the Lion Programming Language.

## FAQs

 - *Q.* **How can I start using Lion?**<br>
   *A.* Just download Savannah's SDK that includes the Savannah Runtime Environment. This will let you run Lion scripts.
 - *Q.* **Do I need to purchase a Savannah-integrated product?**<br>
   *A.* No. Savannah's SDK is free and multi-platform, and it contains sensor emulators that will let you start creating your scripts without having to acquire an electronic board that integrates Savannah. However, if you have one, you can use it for testing and deployment.
 - *Q.* **Is Lion a stand-alone language or it needs Savannah for its execution?**<br>
   *A.* Out-of-the-box, Lion is integrated into the Savannah SDK. Refer to the question below.
 - *Q.* **Can I use Lion with boards or sensors that do not have Savannah integrated?**<br>
   *A.* No support is provided to products that do not integrate the Savannah Framework as their data harvesting system. However, you can create your own language binds to anything your custom frameworks or applications. Lion separates language semantics from the software development framework and runtime so that it is fully customisable and it can stand alone.
 - *Q.* **Can I contribute to Lion's development?**<br>
   *A.* Sure! Feel free to read through the repository, fork it, and submit a pull request or an issue.
