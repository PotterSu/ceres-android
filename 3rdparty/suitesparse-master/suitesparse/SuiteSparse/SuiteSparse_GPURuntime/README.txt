SuiteSparse_GPURuntime Copyright (c) 2013-2016, Timothy A. Davis,
Sencer Nuri Yeralan, and Sanjay Ranka.  http://www.suitesparse.com

SuiteSparse_GPURuntime provides helper functions for the GPU.

FOR LINUX/UNIX/Mac USERS who want to use the C++ callable library:

    To compile the SuiteSparse_GPURuntime C++ library, in the Unix shell, do:

        cd Lib ; make

    or just 'make' in this directory. Both static (*.a) and shared
    (*.so) libraries are created.

    To install the librari into /usr/local/lib, do 'make install'.
    The include files are not copied into /usr/local/include, since this
    library is currently not meant to be user-callable.  It is used only
    by SuiteSparseQR.

    To remove it from /usr/local/lib, do 'make uninstall'.

--------------------------------------------------------------------------------

SuiteSparse_GPURuntime is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by the Free
Software Foundation; either version 2 of the License, or (at your option) any
later version.

SuiteSparse_GPURuntime is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or
FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more
details.

You should have received a copy of the GNU General Public License along with
this Module; if not, write to the Free Software Foundation, Inc., 51 Franklin
Street, Fifth Floor, Boston, MA  02110-1301, USA.
