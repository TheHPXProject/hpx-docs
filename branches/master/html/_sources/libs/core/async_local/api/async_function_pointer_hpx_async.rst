
..
    Copyright (C) 2022-2026 Dimitra Karatza
    Copyright (C) 2022-2026 The STE||AR Group

    SPDX-License-Identifier: BSL-1.0
    Distributed under the Boost Software License, Version 1.0. (See accompanying
    file LICENSE_1_0.txt or copy at http://www.boost.org/LICENSE_1_0.txt)

.. _modules_async_function_pointer_hpx_async_api:

----------
hpx::async
----------

Defined in header :hpx-header:`libs/full/include/include,hpx/future.hpp`.

See :ref:`public_api` for a list of names and headers that are part of the public
|hpx| API.


See also:

   - :ref:`hpx::post <modules_async_function_pointer_hpx_post_api>`

.. seealso::
   :hpx:func:`hpx::async (distributed)`

.. doxygenfunction:: hpx::async(F && f, Ts &&... ts)
   :project: hpx
.. doxygenfunction:: hpx::async(Ts &&... ts)
   :project: hpx
.. doxygenfunction:: hpx::async(Where && where, Ts &&... ts)
   :project: hpx
.. doxygenfunction:: hpx::async(F && f, Ts &&... ts)
   :project: hpx
.. doxygenfunction:: hpx::async(Executor && exec, hpx::sycl::experimental::sycl_executor::queue_function_ptr_t< Ts... > && f, Ts &&... ts)
   :project: hpx
.. doxygenfunction:: hpx::async(Action && action, Target && target, Ts &&... ts)
   :project: hpx
