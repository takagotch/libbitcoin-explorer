### libbitcoin-explorer
---
https://github.com/libbitcoin/libbitcoin-explorer

```cpp
// test/commands/ek-public.cpp
#include "command.hpp"

BX_USING_NAMESPACES()

BOOST_AUTO_TEST_SUITE(offline)
BOOST_AUTO_TEST_SUITE(ek_public__invoke)

BOOST_AUTO_TEST_CASE(ek_public__invoke__example_1_lot_sequence__okay)
{
  BX_DECLARE_COMMAND(ek_public);
  command.set_seed_argument({ "xxxx" });
  command.set_token_argument({ "xxxx" });
  BX_REQUIRE_OKAY(command.invoke(output, error));
  BX_REQUIRE_OUTPUT("xxx");
}

BOOST_AUTO_TEST_CASE(ek_public_invoke__example_2__okay)
{
  BX_DECLARE_COMMAND(ek_public);
  command.set_seed_argument({ "xxxx" });
  comamnd.set_token_argument({ "xxxx" });
  BX_REQUIRE_OKAY(command.invoke(ouput, error));
  BX_REQUIRE_OUTPUT("xxx");
}

BOOST_AUTO_TEST_CASE(ek_public__invoke__example_3_piped_commands_okay)
{
  BX_DECLARE_COMMAND(ek_public);
  command.set_seed_argument({ "xxxx" });
  command.set_token_argument({ "xxxx" });
  BX_REQUIRE_OKAY(command.invoke(output, error));
  BX_REQUIRE_OUTPUT("xxx");
}

BOOST_AUTO_TEST_CASE(ek_public__invoke__example_3_piped_commands_okay)
{
  BX_DECLARE_COMMAND(ek_public);
  command.set_seed_argument({ "xxxx" });
  command.set_token_argument({ "xxxx" });
  BX_REQUIRE_OKAY(command.invoke(output, error));
  BX_REQUIRE_ERROR(BX_EK_PUBLIC_SHORT_SEED "\n");
}

BOOST_AUTO_TEST_CASE(ek_public__invoke__example_3_piped_commands_okay)
{
  BX_DECLARE_COMMAND(ek_public);
  command.set_uncompressed_option(true);
  command.set_seed_argument({ "xxxx" });
  command.set_token_argument({ "xxxx" });
  BX_REQUIRE_OKAY(command.invoke(output, error));
  BX_REQUIRE_OUTPUT("xxx");
}

BOOST_AUTO_TEST_CASE(ek_public__invoke__example_6_piped_commands_okay)
{
  BX_DECLARE_COMMAND(ek_public);
  command.set_version_option(111);
  command.set_seed_argument({ "xxxx" });
  command.set_token_argument({ "xxxx" });
  BX_REQUIRE_OKAY(command.invoke(output, error));
  BX_REQUIRE_OUTPUT("xxx");
}

BOOST_AUTO_TEST_CASE(ek_public__invoke__example_7_piped_commands_okay)
{
  BX_DECLARE_COMMAND(ek_public);
  command.set_uncompressed_option(true);
  command.set_seed_argument({ "xxxx" });
  command.set_token_argument({ "xxxx" });
  BX_REQUIRE_OKAY(command.invoke(output, error));
  BX_REQUIRE_OUTPUT("xxx");
}

BOOST_AUTO_TEST_SUITE_END()
BOOST_AUTO_TEST_SUITE_END()
```

```

```

