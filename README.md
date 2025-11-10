# Function-Modifier-Draft-3
function applyModifier(
        uint _base,
        int _modifier
    ) external pure override returns (uint) {
        return uint(int256(_base) + _modifier);
    }
