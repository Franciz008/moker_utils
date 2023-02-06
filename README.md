# mock

仿照mock.js生成随机数据

## Basic

### character
    m_mock.mock("@character()"):X
    m_mock.mock("@character('lower')"):f
    m_mock.mock("@character('upper')"):E
    m_mock.mock("@character('number')"):4
    m_mock.mock("@character('symbol')"):)
    m_mock.mock("@character('aeiou')"):o

### integer
    m_mock.mock("@integer(2,4)"):3
    m_mock.mock("@integer(3)"):4941869747671297
    m_mock.mock("@integer()"):-3191979912544874

### boolean
    m_mock.mock("@boolean(2,4)"):False
    m_mock.mock("@boolean(3)"):True
    m_mock.mock("@boolean()"):False

### float
    m_mock.mock("@float(2,4)"):2.937
    m_mock.mock("@float(3)"):229342892631770.44
    m_mock.mock("@float()"):872256.00439

### string
    m_mock.mock("@string(2)"):$@
    m_mock.mock("@string("lower", 3)"):nyx
    m_mock.mock("@string("upper", 3)"):HWS
    m_mock.mock("@string("number", 3)"):987
    m_mock.mock("@string("symbol", 3)"):^)<
    m_mock.mock("@string("aeiou", 3)"):iee
    m_mock.mock("@string("lower", 1, 3)"):gn
    m_mock.mock("@string("upper", 1, 3)"):DSZ
    m_mock.mock("@string("number", 1, 3)"):773
    m_mock.mock("@string("symbol", 1, 3)"):#(<
    m_mock.mock("@string("aeiou", 1, 3)"):eaa
    m_mock.mock("@string("chinese", 1, 3)"):太主截
    m_mock.mock("@string("cn_symbol", 1, 3)"):『“
    m_mock.mock("@string("cn_string", 3, 9)"):〕壁辨钻眠素举沾。
    m_mock.mock("@string("cn_string", 1)"):柔