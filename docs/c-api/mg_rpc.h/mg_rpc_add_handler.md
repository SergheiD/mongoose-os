---
title: "mg_rpc_add_handler()"
decl_name: "mg_rpc_add_handler"
symbol_kind: "func"
signature: |
  void mg_rpc_add_handler(struct mg_rpc *c, const struct mg_str method,
                          mg_handler_cb_t cb, void *cb_arg);
---

Add a method handler. 

