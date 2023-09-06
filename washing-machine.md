# Washing machine state

## START
topic:v1cdti/app/get/6310301027/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301027",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "START"
}

## READY
topic:v1cdti/app/get/6310301027/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301027",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "READY"
}

## FILLWATER
topic:v1cdti/app/get/6310301027/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301027",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "FILLWATER"
}

## HEATWATER
topic:v1cdti/app/get/6310301027/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301027",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "HEATWATER"
}

## WASH
topic:v1cdti/app/get/6310301027/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301027",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "WASH"
}

## RINSE
topic:v1cdti/app/get/6310301027/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301027",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "RINSE"
}

## SPIN
topic:v1cdti/app/get/6310301027/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301027",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "SPIN"
}

# Operation state

## DOORCLOSE
topic:v1cdti/app/set/6310301027/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301027",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "OP_STATUS",
    "value"     :   "DOORCLOSE"
}

## WATERFULLLEVEL
topic:v1cdti/app/set/6310301027/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301027",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "OP_STATUS",
    "value"     :   "WATERFULLLEVEL"
}

## TEMPERATUREREACHED
topic:v1cdti/app/set/6310301027/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301027",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "OP_STATUS",
    "value"     :   "TEMPERATUREREACHED"
}


# FAULT state

## TIMEOUT
topic:v1cdti/app/get/6310301027/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301027",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT_STATUS",
    "value"     :   "TIMEOUT"
}

## OUTOFBALANCE
topic:v1cdti/app/get/6310301027/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301027",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT_STATUS",
    "value"     :   "OUTOFBALANCE"
}

## MOTORFAILURE
topic:v1cdti/app/get/6310301027/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301027",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT_STATUS",
    "value"     :   "MOTORFAILURE"
}

## FAULTCLEARED
topic:v1cdti/app/get/6310301027/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301027",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT_STATUS",
    "value"     :   "FAULTCLEARED"
}