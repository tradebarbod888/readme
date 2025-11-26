float risk_per_unit_short = (sl_short_price - close) * point_value
float pos_size_short = risk_capital / risk_per_unit_short
float tp1_short_price = close - (sl_short_price - close) * tp1RR
float tp2_short_price = close - (sl_short_price - close) * tp2RR
