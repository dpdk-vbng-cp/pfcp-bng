################################################################################
# Copyright (c) 2020 Ricardo Santos, BISDN GmbH
#
# Licensed under the License terms and conditions for use, reproduction,
# and distribution of OPENAIR 5G software (the “License”);
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#    https://www.openairinterface.org/?page_id=698
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
################################################################################
add_library (DPDK_TELNET STATIC
  AsioTelnetClient.cpp
  )


