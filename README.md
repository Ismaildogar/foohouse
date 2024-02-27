select * from card_lists WHERE card_status = 'NEW'
and issuer =1 and (is_payed =1 or requested_by in (1310, 1485))
