.. list-table::
   :header-rows: 1

   * * Method
     * Description
     * From where?

   * * ssh
     * Standard way of connecting via command line.  Hostname is
       ``triton.aalto.fi``

       >Linux/Mac: ``ssh username@triton.aalto.fi``

       >Windows: PuTTY (install yourself) or WSL+Linux/mac command.

     * Connections only from VPN and Aalto networks.
       ``kosh.aalto.fi`` is a good proxy host if you are not there:
       ``ssh -J username@kosh.aalto.fi username@triton.aalto.fi``

   * * VDI
     * "Virtual desktop interface", https://vdi.aalto.fi, from there you have to
       ``ssh`` to Triton (previous row) and can run graphical
       programs via SSH.
     * Whole internet

   * * Jupyter
     * https://jupyter.triton.aalto.fi provides the Jupyter interface
       directly on Triton (including command line).
     * Whole internet
