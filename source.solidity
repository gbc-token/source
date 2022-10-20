contract Contract {
    function main() {
        memory[0x40:0x60] = 0x80;
        var var0 = msg.value;
    
        if (var0) { revert(memory[0x00:0x00]); }
    
        if (msg.data.length < 0x04) { revert(memory[0x00:0x00]); }
    
        var0 = msg.data[0x00:0x20] >> 0xe0;
    
        if (0x893d20e8 > var0) {
            if (0x313ce567 > var0) {
                if (var0 == 0x06fdde03) {
                    // Dispatch table entry for name()
                    var var1 = 0x010d;
                    var1 = name();
                
                label_010D:
                    var temp0 = memory[0x40:0x60];
                    memory[temp0:temp0 + 0x20] = 0x20;
                    var temp1 = var1;
                    memory[temp0 + 0x20:temp0 + 0x20 + 0x20] = memory[temp1:temp1 + 0x20];
                    var var2 = temp0;
                    var var3 = var2;
                    var var4 = var3 + 0x40;
                    var var5 = temp1 + 0x20;
                    var var6 = memory[temp1:temp1 + 0x20];
                    var var7 = var6;
                    var var8 = var4;
                    var var9 = var5;
                    var var10 = 0x00;
                
                    if (var10 >= var7) {
                    label_0147:
                        var temp2 = var6;
                        var4 = temp2 + var4;
                        var5 = temp2 & 0x1f;
                    
                        if (!var5) {
                            var temp3 = memory[0x40:0x60];
                            return memory[temp3:temp3 + var4 - temp3];
                        } else {
                            var temp4 = var5;
                            var temp5 = var4 - temp4;
                            memory[temp5:temp5 + 0x20] = ~(0x0100 ** (0x20 - temp4) - 0x01) & memory[temp5:temp5 + 0x20];
                            var temp6 = memory[0x40:0x60];
                            return memory[temp6:temp6 + (temp5 + 0x20) - temp6];
                        }
                    } else {
                    label_0138:
                        var temp7 = var10;
                        memory[temp7 + var8:temp7 + var8 + 0x20] = memory[temp7 + var9:temp7 + var9 + 0x20];
                        var10 = temp7 + 0x20;
                    
                        if (var10 >= var7) { goto label_0147; }
                        else { goto label_0138; }
                    }
                } else if (var0 == 0x095ea7b3) {
                    // Dispatch table entry for approve(address,uint256)
                    var1 = 0x01ae;
                    var2 = 0x04;
                    var3 = msg.data.length - var2;
                
                    if (var3 < 0x40) { revert(memory[0x00:0x00]); }
                
                    var1 = approve(var2, var3);
                
                label_01AE:
                    var temp8 = memory[0x40:0x60];
                    memory[temp8:temp8 + 0x20] = !!var1;
                    var temp9 = memory[0x40:0x60];
                    return memory[temp9:temp9 + temp8 - temp9 + 0x20];
                } else if (var0 == 0x18160ddd) {
                    // Dispatch table entry for totalSupply()
                    var1 = 0x01ca;
                    var1 = totalSupply();
                
                label_01CA:
                    var temp10 = memory[0x40:0x60];
                    memory[temp10:temp10 + 0x20] = var1;
                    var temp11 = memory[0x40:0x60];
                    return memory[temp11:temp11 + temp10 - temp11 + 0x20];
                } else if (var0 == 0x23b872dd) {
                    // Dispatch table entry for transferFrom(address,address,uint256)
                    var1 = 0x01ae;
                    var2 = 0x04;
                    var3 = msg.data.length - var2;
                
                    if (var3 < 0x60) { revert(memory[0x00:0x00]); }
                
                    var temp12 = (0x01 << 0xa0) - 0x01;
                    var temp13 = var2;
                    var2 = temp12 & msg.data[temp13:temp13 + 0x20];
                    var3 = temp12 & msg.data[temp13 + 0x20:temp13 + 0x20 + 0x20];
                    var4 = msg.data[temp13 + 0x40:temp13 + 0x40 + 0x20];
                    var5 = 0x00;
                    var6 = 0x044f;
                    var7 = var2;
                    var8 = var3;
                    var9 = var4;
                    func_0912(var7, var8, var9);
                    var6 = 0x04c5;
                    var7 = var2;
                    var8 = 0x045b;
                    var8 = func_0822();
                    var9 = 0x04c0;
                    var10 = var4;
                    var temp14 = memory[0x40:0x60];
                    var var11 = temp14;
                    memory[0x40:0x60] = var11 + 0x60;
                    memory[var11:var11 + 0x20] = 0x28;
                    memory[var11 + 0x20:var11 + 0x20 + 0x28] = code[0x0d6a:0x0d92];
                    memory[0x00:0x20] = var2 & (0x01 << 0xa0) - 0x01;
                    memory[0x20:0x40] = 0x02;
                    var var12 = keccak256(memory[0x00:0x40]);
                    var var13 = 0x00;
                    var var14 = 0x0499;
                    var14 = func_0822();
                    var9 = func_0499(var10, var11, var12, var13, var14);
                
                    if (!(var7 & (0x01 << 0xa0) - 0x01)) {
                        var temp27 = memory[0x40:0x60];
                        memory[temp27:temp27 + 0x20] = 0x461bcd << 0xe5;
                        var temp28 = temp27 + 0x04;
                        var temp29 = temp28 + 0x20;
                        memory[temp28:temp28 + 0x20] = temp29 - temp28;
                        memory[temp29:temp29 + 0x20] = 0x24;
                        var temp30 = temp29 + 0x20;
                        memory[temp30:temp30 + 0x24] = code[0x0d20:0x0d44];
                        var temp31 = memory[0x40:0x60];
                        revert(memory[temp31:temp31 + (temp30 + 0x40) - temp31]);
                    } else if (var8 & (0x01 << 0xa0) - 0x01) {
                        var temp15 = (0x01 << 0xa0) - 0x01;
                        var temp16 = var7 & temp15;
                        memory[0x00:0x20] = temp16;
                        memory[0x20:0x40] = 0x02;
                        var temp17 = keccak256(memory[0x00:0x40]);
                        var temp18 = var8 & temp15;
                        memory[0x00:0x20] = temp18;
                        memory[0x20:0x40] = temp17;
                        var temp19 = var9;
                        storage[keccak256(memory[0x00:0x40])] = temp19;
                        var temp20 = memory[0x40:0x60];
                        memory[temp20:temp20 + 0x20] = temp19;
                        var temp21 = memory[0x40:0x60];
                        log(memory[temp21:temp21 + temp20 - temp21 + 0x20], [0x8c5be1e5ebec7d5bd14f71427d1e84f3dd0314c0f7b2291e5b200ac8c7c3b925, stack[-3] & (0x01 << 0xa0) - 0x01, stack[-2] & (0x01 << 0xa0) - 0x01]);
                        // Error: Could not resolve jump destination!
                    } else {
                        var temp22 = memory[0x40:0x60];
                        memory[temp22:temp22 + 0x20] = 0x461bcd << 0xe5;
                        var temp23 = temp22 + 0x04;
                        var temp24 = temp23 + 0x20;
                        memory[temp23:temp23 + 0x20] = temp24 - temp23;
                        memory[temp24:temp24 + 0x20] = 0x22;
                        var temp25 = temp24 + 0x20;
                        memory[temp25:temp25 + 0x22] = code[0x0e00:0x0e22];
                        var temp26 = memory[0x40:0x60];
                        revert(memory[temp26:temp26 + (temp25 + 0x40) - temp26]);
                    }
                } else { revert(memory[0x00:0x00]); }
            } else if (var0 == 0x313ce567) {
                // Dispatch table entry for decimals()
                var1 = 0x021a;
                var1 = decimals();
                var temp32 = memory[0x40:0x60];
                memory[temp32:temp32 + 0x20] = var1 & 0xff;
                var temp33 = memory[0x40:0x60];
                return memory[temp33:temp33 + temp32 - temp33 + 0x20];
            } else if (var0 == 0x39509351) {
                // Dispatch table entry for increaseAllowance(address,uint256)
                var1 = 0x01ae;
                var2 = 0x04;
                var3 = msg.data.length - var2;
            
                if (var3 < 0x40) { revert(memory[0x00:0x00]); }
            
                var temp34 = var2;
                var2 = msg.data[temp34:temp34 + 0x20] & (0x01 << 0xa0) - 0x01;
                var3 = msg.data[temp34 + 0x20:temp34 + 0x20 + 0x20];
                var4 = 0x00;
                var5 = 0x0433;
                var6 = 0x04e5;
                var6 = func_0822();
                func_04E5(var2, var3, var6);
            
            label_0433:
                var1 = 0x01;
                // Error: Could not resolve jump destination!
            } else if (var0 == 0x70a08231) {
                // Dispatch table entry for balanceOf(address)
                var1 = 0x01ca;
                var2 = 0x04;
                var3 = msg.data.length - var2;
            
                if (var3 < 0x20) { revert(memory[0x00:0x00]); }
            
                var1 = balanceOf(var2, var3);
                goto label_01CA;
            } else if (var0 == 0x715018a6) {
                // Dispatch table entry for renounceOwnership()
                var1 = 0x028a;
                renounceOwnership();
                stop();
            } else { revert(memory[0x00:0x00]); }
        } else if (0xa457c2d7 > var0) {
            if (var0 == 0x893d20e8) {
                // Dispatch table entry for getOwner()
                var1 = 0x0294;
                var1 = getOwner();
            
            label_0294:
                var temp35 = memory[0x40:0x60];
                memory[temp35:temp35 + 0x20] = var1 & (0x01 << 0xa0) - 0x01;
                var temp36 = memory[0x40:0x60];
                return memory[temp36:temp36 + temp35 - temp36 + 0x20];
            } else if (var0 == 0x8da5cb5b) {
                // Dispatch table entry for owner()
                var1 = 0x0294;
                var1 = owner();
                goto label_0294;
            } else if (var0 == 0x95d89b41) {
                // Dispatch table entry for symbol()
                var1 = 0x010d;
                var1 = symbol();
                goto label_010D;
            } else if (var0 == 0xa0712d68) {
                // Dispatch table entry for mint(uint256)
                var1 = 0x01ae;
                var2 = 0x04;
                var3 = msg.data.length - var2;
            
                if (var3 < 0x20) { revert(memory[0x00:0x00]); }
            
                var1 = mint(var2, var3);
                goto label_01AE;
            } else { revert(memory[0x00:0x00]); }
        } else if (var0 == 0xa457c2d7) {
            // Dispatch table entry for decreaseAllowance(address,uint256)
            var1 = 0x01ae;
            var2 = 0x04;
            var3 = msg.data.length - var2;
        
            if (var3 < 0x40) { revert(memory[0x00:0x00]); }
        
            var temp37 = var2;
            var2 = msg.data[temp37:temp37 + 0x20] & (0x01 << 0xa0) - 0x01;
            var3 = msg.data[temp37 + 0x20:temp37 + 0x20 + 0x20];
            var4 = 0x00;
            var5 = 0x0433;
            var6 = 0x070c;
            var6 = func_0822();
            func_070C(var2, var3, var6);
            goto label_0433;
        } else if (var0 == 0xa9059cbb) {
            // Dispatch table entry for transfer(address,uint256)
            var1 = 0x01ae;
            var2 = 0x04;
            var3 = msg.data.length - var2;
        
            if (var3 < 0x40) { revert(memory[0x00:0x00]); }
        
            var temp38 = var2;
            var2 = msg.data[temp38:temp38 + 0x20] & (0x01 << 0xa0) - 0x01;
            var3 = msg.data[temp38 + 0x20:temp38 + 0x20 + 0x20];
            var4 = 0x00;
            var5 = 0x0433;
            var6 = 0x077a;
            var6 = func_0822();
            func_077A(var2, var3, var6);
            goto label_0433;
        } else if (var0 == 0xdd62ed3e) {
            // Dispatch table entry for allowance(address,address)
            var1 = 0x01ca;
            var2 = 0x04;
            var3 = msg.data.length - var2;
        
            if (var3 < 0x40) { revert(memory[0x00:0x00]); }
        
            var1 = allowance(var2, var3);
            goto label_01CA;
        } else if (var0 == 0xf2fde38b) {
            // Dispatch table entry for transferOwnership(address)
            var1 = 0x028a;
            var2 = 0x04;
            var3 = msg.data.length - var2;
        
            if (var3 < 0x20) { revert(memory[0x00:0x00]); }
        
            transferOwnership(var2, var3);
            stop();
        } else { revert(memory[0x00:0x00]); }
    }
    
    function approve(var arg0, var arg1) returns (var r0) {
        var temp0 = arg0;
        arg0 = msg.data[temp0:temp0 + 0x20] & (0x01 << 0xa0) - 0x01;
        arg1 = msg.data[temp0 + 0x20:temp0 + 0x20 + 0x20];
        var var0 = 0x00;
        var var1 = 0x0433;
        var var2 = 0x042c;
        var2 = func_0822();
        func_042C(arg0, arg1, var2);
        return 0x01;
    }
    
    function balanceOf(var arg0, var arg1) returns (var r0) {
        arg0 = msg.data[arg0:arg0 + 0x20] & (0x01 << 0xa0) - 0x01;
        memory[0x00:0x20] = arg0 & (0x01 << 0xa0) - 0x01;
        memory[0x20:0x40] = 0x01;
        return storage[keccak256(memory[0x00:0x40])];
    }
    
    function mint(var arg0, var arg1) returns (var r0) {
        arg0 = msg.data[arg0:arg0 + 0x20];
        arg1 = 0x00;
        var var0 = 0x0684;
        var0 = func_0822();
        var temp0 = (0x01 << 0xa0) - 0x01;
    
        if (var0 & temp0 == temp0 & storage[0x00]) {
            var0 = 0x06f7;
            var var1 = 0x06f1;
            var1 = func_0822();
            func_06F1(arg0, var1);
            return 0x01;
        } else {
            var temp1 = memory[0x40:0x60];
            memory[temp1:temp1 + 0x20] = 0x461bcd << 0xe5;
            memory[temp1 + 0x04:temp1 + 0x04 + 0x20] = 0x20;
            memory[temp1 + 0x24:temp1 + 0x24 + 0x20] = 0x20;
            memory[temp1 + 0x44:temp1 + 0x44 + 0x20] = 0x4f776e61626c653a2063616c6c6572206973206e6f7420746865206f776e6572;
            var temp2 = memory[0x40:0x60];
            revert(memory[temp2:temp2 + temp1 - temp2 + 0x64]);
        }
    }
    
    function allowance(var arg0, var arg1) returns (var r0) {
        var temp0 = (0x01 << 0xa0) - 0x01;
        var temp1 = arg0;
        arg0 = temp0 & msg.data[temp1:temp1 + 0x20];
        arg1 = msg.data[temp1 + 0x20:temp1 + 0x20 + 0x20] & temp0;
        var temp2 = (0x01 << 0xa0) - 0x01;
        memory[0x00:0x20] = temp2 & arg0;
        memory[0x20:0x40] = 0x02;
        var temp3 = keccak256(memory[0x00:0x40]);
        memory[0x00:0x20] = temp2 & arg1;
        memory[0x20:0x40] = temp3;
        return storage[keccak256(memory[0x00:0x40])];
    }
    
    function transferOwnership(var arg0, var arg1) {
        arg0 = msg.data[arg0:arg0 + 0x20] & (0x01 << 0xa0) - 0x01;
        arg1 = 0x07b4;
        arg1 = func_0822();
        var temp0 = (0x01 << 0xa0) - 0x01;
    
        if (arg1 & temp0 == temp0 & storage[0x00]) {
            arg1 = 0x081f;
            var var0 = arg0;
            func_0C5A(var0);
            return;
        } else {
            var temp1 = memory[0x40:0x60];
            memory[temp1:temp1 + 0x20] = 0x461bcd << 0xe5;
            memory[temp1 + 0x04:temp1 + 0x04 + 0x20] = 0x20;
            memory[temp1 + 0x24:temp1 + 0x24 + 0x20] = 0x20;
            memory[temp1 + 0x44:temp1 + 0x44 + 0x20] = 0x4f776e61626c653a2063616c6c6572206973206e6f7420746865206f776e6572;
            var temp2 = memory[0x40:0x60];
            revert(memory[temp2:temp2 + temp1 - temp2 + 0x64]);
        }
    }
    
    function name() returns (var r0) {
        var temp0 = storage[0x06];
        var temp1 = memory[0x40:0x60];
        var temp2 = (temp0 & !(temp0 & 0x01) * 0x0100 + ~0x00) / 0x02;
        memory[0x40:0x60] = temp1 + (temp2 + 0x1f) / 0x20 * 0x20 + 0x20;
        memory[temp1:temp1 + 0x20] = temp2;
        var var0 = 0x60;
        var var1 = temp1;
        var var3 = temp2;
        var var2 = 0x06;
        var var4 = var1 + 0x20;
        var var5 = var2;
        var var6 = var3;
    
        if (!var6) {
        label_0415:
            return var1;
        } else if (0x1f < var6) {
            var temp3 = var4;
            var temp4 = temp3 + var6;
            var4 = temp4;
            memory[0x00:0x20] = var5;
            var temp5 = keccak256(memory[0x00:0x20]);
            memory[temp3:temp3 + 0x20] = storage[temp5];
            var5 = temp5 + 0x01;
            var6 = temp3 + 0x20;
        
            if (var4 <= var6) { goto label_040C; }
        
        label_03F8:
            var temp6 = var5;
            var temp7 = var6;
            memory[temp7:temp7 + 0x20] = storage[temp6];
            var5 = temp6 + 0x01;
            var6 = temp7 + 0x20;
        
            if (var4 > var6) { goto label_03F8; }
        
        label_040C:
            var temp8 = var4;
            var temp9 = temp8 + (var6 - temp8 & 0x1f);
            var6 = temp8;
            var4 = temp9;
            goto label_0415;
        } else {
            var temp10 = var4;
            memory[temp10:temp10 + 0x20] = storage[var5] / 0x0100 * 0x0100;
            var6 = var6;
            var4 = temp10 + 0x20;
            goto label_0415;
        }
    }
    
    function func_042C(var arg0, var arg1, var arg2) {
        var var0 = arg0;
        var var1 = arg1;
    
        if (!(arg2 & (0x01 << 0xa0) - 0x01)) {
            var temp12 = memory[0x40:0x60];
            memory[temp12:temp12 + 0x20] = 0x461bcd << 0xe5;
            var temp13 = temp12 + 0x04;
            var temp14 = temp13 + 0x20;
            memory[temp13:temp13 + 0x20] = temp14 - temp13;
            memory[temp14:temp14 + 0x20] = 0x24;
            var temp15 = temp14 + 0x20;
            memory[temp15:temp15 + 0x24] = code[0x0d20:0x0d44];
            var temp16 = memory[0x40:0x60];
            revert(memory[temp16:temp16 + (temp15 + 0x40) - temp16]);
        } else if (var0 & (0x01 << 0xa0) - 0x01) {
            var temp0 = (0x01 << 0xa0) - 0x01;
            var temp1 = arg2 & temp0;
            memory[0x00:0x20] = temp1;
            memory[0x20:0x40] = 0x02;
            var temp2 = keccak256(memory[0x00:0x40]);
            var temp3 = var0 & temp0;
            memory[0x00:0x20] = temp3;
            memory[0x20:0x40] = temp2;
            var temp4 = var1;
            storage[keccak256(memory[0x00:0x40])] = temp4;
            var temp5 = memory[0x40:0x60];
            memory[temp5:temp5 + 0x20] = temp4;
            var temp6 = memory[0x40:0x60];
            log(memory[temp6:temp6 + temp5 - temp6 + 0x20], [0x8c5be1e5ebec7d5bd14f71427d1e84f3dd0314c0f7b2291e5b200ac8c7c3b925, stack[-3] & (0x01 << 0xa0) - 0x01, stack[-2] & (0x01 << 0xa0) - 0x01]);
            return;
        } else {
            var temp7 = memory[0x40:0x60];
            memory[temp7:temp7 + 0x20] = 0x461bcd << 0xe5;
            var temp8 = temp7 + 0x04;
            var temp9 = temp8 + 0x20;
            memory[temp8:temp8 + 0x20] = temp9 - temp8;
            memory[temp9:temp9 + 0x20] = 0x22;
            var temp10 = temp9 + 0x20;
            memory[temp10:temp10 + 0x22] = code[0x0e00:0x0e22];
            var temp11 = memory[0x40:0x60];
            revert(memory[temp11:temp11 + (temp10 + 0x40) - temp11]);
        }
    }
    
    function totalSupply() returns (var r0) { return storage[0x03]; }
    
    function func_0499(var arg0, var arg1, var arg2, var arg3, var arg4) returns (var r0) {
        var temp0 = arg3;
        memory[temp0:temp0 + 0x20] = arg4 & (0x01 << 0xa0) - 0x01;
        memory[temp0 + 0x20:temp0 + 0x20 + 0x20] = arg2;
        var temp1 = arg0;
        arg0 = storage[keccak256(memory[0x00:0x00 + temp0 + 0x40])];
        arg2 = arg1;
        arg1 = temp1;
        r0 = func_0A70(arg0, arg1, arg2);
        // Error: Could not resolve method call return address!
    }
    
    function decimals() returns (var r0) { return storage[0x04] & 0xff; }
    
    function func_04E5(var arg0, var arg1, var arg2) {
        var var0 = arg0;
        var var1 = 0x04c0;
        var var2 = arg1;
        var var3 = 0x02;
        var var4 = 0x00;
        var var5 = 0x04f6;
        var5 = func_0822();
        var1 = func_04F6(arg0, var2, var3, var4, var5);
    
        if (!(arg2 & (0x01 << 0xa0) - 0x01)) {
            var temp12 = memory[0x40:0x60];
            memory[temp12:temp12 + 0x20] = 0x461bcd << 0xe5;
            var temp13 = temp12 + 0x04;
            var temp14 = temp13 + 0x20;
            memory[temp13:temp13 + 0x20] = temp14 - temp13;
            memory[temp14:temp14 + 0x20] = 0x24;
            var temp15 = temp14 + 0x20;
            memory[temp15:temp15 + 0x24] = code[0x0d20:0x0d44];
            var temp16 = memory[0x40:0x60];
            revert(memory[temp16:temp16 + (temp15 + 0x40) - temp16]);
        } else if (var0 & (0x01 << 0xa0) - 0x01) {
            var temp0 = (0x01 << 0xa0) - 0x01;
            var temp1 = arg2 & temp0;
            memory[0x00:0x20] = temp1;
            memory[0x20:0x40] = 0x02;
            var temp2 = keccak256(memory[0x00:0x40]);
            var temp3 = var0 & temp0;
            memory[0x00:0x20] = temp3;
            memory[0x20:0x40] = temp2;
            var temp4 = var1;
            storage[keccak256(memory[0x00:0x40])] = temp4;
            var temp5 = memory[0x40:0x60];
            memory[temp5:temp5 + 0x20] = temp4;
            var temp6 = memory[0x40:0x60];
            log(memory[temp6:temp6 + temp5 - temp6 + 0x20], [0x8c5be1e5ebec7d5bd14f71427d1e84f3dd0314c0f7b2291e5b200ac8c7c3b925, stack[-3] & (0x01 << 0xa0) - 0x01, stack[-2] & (0x01 << 0xa0) - 0x01]);
            return;
        } else {
            var temp7 = memory[0x40:0x60];
            memory[temp7:temp7 + 0x20] = 0x461bcd << 0xe5;
            var temp8 = temp7 + 0x04;
            var temp9 = temp8 + 0x20;
            memory[temp8:temp8 + 0x20] = temp9 - temp8;
            memory[temp9:temp9 + 0x20] = 0x22;
            var temp10 = temp9 + 0x20;
            memory[temp10:temp10 + 0x22] = code[0x0e00:0x0e22];
            var temp11 = memory[0x40:0x60];
            revert(memory[temp11:temp11 + (temp10 + 0x40) - temp11]);
        }
    }
    
    function func_04F6(var arg0, var arg1, var arg2, var arg3, var arg4) returns (var r0) {
        var temp0 = (0x01 << 0xa0) - 0x01;
        var temp1 = arg3;
        memory[temp1:temp1 + 0x20] = temp0 & arg4;
        memory[temp1 + 0x20:temp1 + 0x20 + 0x20] = arg2;
        var temp2 = keccak256(memory[0x00:0x00 + temp1 + 0x40]);
        memory[0x00:0x20] = arg0 & temp0;
        memory[0x20:0x40] = temp2;
        arg2 = arg1;
        arg1 = storage[keccak256(memory[0x00:0x40])];
        r0 = func_0B07(arg1, arg2);
        // Error: Could not resolve method call return address!
    }
    
    function renounceOwnership() {
        var var0 = 0x054f;
        var0 = func_0822();
        var temp0 = (0x01 << 0xa0) - 0x01;
    
        if (var0 & temp0 == temp0 & storage[0x00]) {
            log(memory[memory[0x40:0x60]:memory[0x40:0x60] + 0x00], [0x8be0079c531659141344cd1fd0a4f28419497f9722a3daafe3b4186f6b6457e0, storage[0x00] & (0x01 << 0xa0) - 0x01, 0x00]);
            storage[0x00] = storage[0x00] & ~((0x01 << 0xa0) - 0x01);
            return;
        } else {
            var temp1 = memory[0x40:0x60];
            memory[temp1:temp1 + 0x20] = 0x461bcd << 0xe5;
            memory[temp1 + 0x04:temp1 + 0x04 + 0x20] = 0x20;
            memory[temp1 + 0x24:temp1 + 0x24 + 0x20] = 0x20;
            memory[temp1 + 0x44:temp1 + 0x44 + 0x20] = 0x4f776e61626c653a2063616c6c6572206973206e6f7420746865206f776e6572;
            var temp2 = memory[0x40:0x60];
            revert(memory[temp2:temp2 + temp1 - temp2 + 0x64]);
        }
    }
    
    function getOwner() returns (var r0) {
        var var0 = 0x00;
        var var1 = 0x0605;
        return owner();
    }
    
    function owner() returns (var r0) { return storage[0x00] & (0x01 << 0xa0) - 0x01; }
    
    function symbol() returns (var r0) {
        var temp0 = storage[0x05];
        var temp1 = memory[0x40:0x60];
        var temp2 = (temp0 & !(temp0 & 0x01) * 0x0100 + ~0x00) / 0x02;
        memory[0x40:0x60] = temp1 + (temp2 + 0x1f) / 0x20 * 0x20 + 0x20;
        memory[temp1:temp1 + 0x20] = temp2;
        var var0 = 0x60;
        var var1 = temp1;
        var var3 = temp2;
        var var2 = 0x05;
        var var4 = var1 + 0x20;
        var var5 = var2;
        var var6 = var3;
    
        if (!var6) {
        label_0415:
            return var1;
        } else if (0x1f < var6) {
            var temp3 = var4;
            var temp4 = temp3 + var6;
            var4 = temp4;
            memory[0x00:0x20] = var5;
            var temp5 = keccak256(memory[0x00:0x20]);
            memory[temp3:temp3 + 0x20] = storage[temp5];
            var5 = temp5 + 0x01;
            var6 = temp3 + 0x20;
        
            if (var4 <= var6) { goto label_040C; }
        
        label_03F8:
            var temp6 = var5;
            var temp7 = var6;
            memory[temp7:temp7 + 0x20] = storage[temp6];
            var5 = temp6 + 0x01;
            var6 = temp7 + 0x20;
        
            if (var4 > var6) { goto label_03F8; }
        
        label_040C:
            var temp8 = var4;
            var temp9 = temp8 + (var6 - temp8 & 0x1f);
            var6 = temp8;
            var4 = temp9;
            goto label_0415;
        } else {
            var temp10 = var4;
            memory[temp10:temp10 + 0x20] = storage[var5] / 0x0100 * 0x0100;
            var4 = temp10 + 0x20;
            var6 = var6;
            goto label_0415;
        }
    }
    
    function func_06F1(var arg0, var arg1) {
        var var0 = arg0;
    
        if (arg1 & (0x01 << 0xa0) - 0x01) {
            var var2 = storage[0x03];
            var var1 = 0x0bd6;
            var var3 = var0;
            var1 = func_0B07(var2, var3);
            storage[0x03] = var1;
            memory[0x00:0x20] = arg1 & (0x01 << 0xa0) - 0x01;
            memory[0x20:0x40] = 0x01;
            var2 = storage[keccak256(memory[0x00:0x40])];
            var1 = 0x0c02;
            var3 = var0;
            var1 = func_0B07(var2, var3);
            var temp0 = arg1 & (0x01 << 0xa0) - 0x01;
            memory[0x00:0x20] = temp0;
            memory[0x20:0x40] = 0x01;
            storage[keccak256(memory[0x00:0x40])] = var1;
            var temp1 = memory[0x40:0x60];
            memory[temp1:temp1 + 0x20] = var0;
            var temp2 = memory[0x40:0x60];
            log(memory[temp2:temp2 + temp1 - temp2 + 0x20], [0xddf252ad1be2c89b69c2b068fc378daa952ba7f163c4a11628f55a4df523b3ef, 0x00, stack[-3] & (0x01 << 0xa0) - 0x01]);
            return;
        } else {
            var temp3 = memory[0x40:0x60];
            memory[temp3:temp3 + 0x20] = 0x461bcd << 0xe5;
            memory[temp3 + 0x04:temp3 + 0x04 + 0x20] = 0x20;
            memory[temp3 + 0x24:temp3 + 0x24 + 0x20] = 0x1f;
            memory[temp3 + 0x44:temp3 + 0x44 + 0x20] = 0x42455032303a206d696e7420746f20746865207a65726f206164647265737300;
            var temp4 = memory[0x40:0x60];
            revert(memory[temp4:temp4 + temp3 - temp4 + 0x64]);
        }
    }
    
    function func_070C(var arg0, var arg1, var arg2) {
        var var0 = arg0;
        var var1 = 0x04c0;
        var var2 = arg1;
        var temp0 = memory[0x40:0x60];
        var var3 = temp0;
        memory[0x40:0x60] = var3 + 0x60;
        memory[var3:var3 + 0x20] = 0x25;
        memory[var3 + 0x20:var3 + 0x20 + 0x25] = code[0x0ddb:0x0e00];
        var var4 = 0x02;
        var var5 = 0x00;
        var var6 = 0x0736;
        var6 = func_0822();
        var1 = func_0736(arg0, var2, var3, var4, var5, var6);
    
        if (!(arg2 & (0x01 << 0xa0) - 0x01)) {
            var temp13 = memory[0x40:0x60];
            memory[temp13:temp13 + 0x20] = 0x461bcd << 0xe5;
            var temp14 = temp13 + 0x04;
            var temp15 = temp14 + 0x20;
            memory[temp14:temp14 + 0x20] = temp15 - temp14;
            memory[temp15:temp15 + 0x20] = 0x24;
            var temp16 = temp15 + 0x20;
            memory[temp16:temp16 + 0x24] = code[0x0d20:0x0d44];
            var temp17 = memory[0x40:0x60];
            revert(memory[temp17:temp17 + (temp16 + 0x40) - temp17]);
        } else if (var0 & (0x01 << 0xa0) - 0x01) {
            var temp1 = (0x01 << 0xa0) - 0x01;
            var temp2 = arg2 & temp1;
            memory[0x00:0x20] = temp2;
            memory[0x20:0x40] = 0x02;
            var temp3 = keccak256(memory[0x00:0x40]);
            var temp4 = var0 & temp1;
            memory[0x00:0x20] = temp4;
            memory[0x20:0x40] = temp3;
            var temp5 = var1;
            storage[keccak256(memory[0x00:0x40])] = temp5;
            var temp6 = memory[0x40:0x60];
            memory[temp6:temp6 + 0x20] = temp5;
            var temp7 = memory[0x40:0x60];
            log(memory[temp7:temp7 + temp6 - temp7 + 0x20], [0x8c5be1e5ebec7d5bd14f71427d1e84f3dd0314c0f7b2291e5b200ac8c7c3b925, stack[-3] & (0x01 << 0xa0) - 0x01, stack[-2] & (0x01 << 0xa0) - 0x01]);
            return;
        } else {
            var temp8 = memory[0x40:0x60];
            memory[temp8:temp8 + 0x20] = 0x461bcd << 0xe5;
            var temp9 = temp8 + 0x04;
            var temp10 = temp9 + 0x20;
            memory[temp9:temp9 + 0x20] = temp10 - temp9;
            memory[temp10:temp10 + 0x20] = 0x22;
            var temp11 = temp10 + 0x20;
            memory[temp11:temp11 + 0x22] = code[0x0e00:0x0e22];
            var temp12 = memory[0x40:0x60];
            revert(memory[temp12:temp12 + (temp11 + 0x40) - temp12]);
        }
    }
    
    function func_0736(var arg0, var arg1, var arg2, var arg3, var arg4, var arg5) returns (var r0) {
        var temp0 = (0x01 << 0xa0) - 0x01;
        var temp1 = arg4;
        memory[temp1:temp1 + 0x20] = temp0 & arg5;
        memory[temp1 + 0x20:temp1 + 0x20 + 0x20] = arg3;
        var temp2 = keccak256(memory[0x00:0x00 + temp1 + 0x40]);
        memory[0x00:0x20] = arg0 & temp0;
        memory[0x20:0x40] = temp2;
        var temp3 = arg1;
        arg1 = storage[keccak256(memory[0x00:0x40])];
        var temp4 = arg2;
        arg2 = temp3;
        arg3 = temp4;
        r0 = func_0A70(arg1, arg2, arg3);
        // Error: Could not resolve method call return address!
    }
    
    function func_077A(var arg0, var arg1, var arg2) {
        var var0 = arg0;
        var var1 = arg1;
        func_0912(arg2, var0, var1);
        // Error: Could not resolve method call return address!
    }
    
    function func_0822() returns (var r0) { return msg.sender; }
    
    function func_0912(var arg0, var arg1, var arg2) {
        if (!(arg0 & (0x01 << 0xa0) - 0x01)) {
            var temp11 = memory[0x40:0x60];
            memory[temp11:temp11 + 0x20] = 0x461bcd << 0xe5;
            var temp12 = temp11 + 0x04;
            var temp13 = temp12 + 0x20;
            memory[temp12:temp12 + 0x20] = temp13 - temp12;
            memory[temp13:temp13 + 0x20] = 0x25;
            var temp14 = temp13 + 0x20;
            memory[temp14:temp14 + 0x25] = code[0x0cfb:0x0d20];
            var temp15 = memory[0x40:0x60];
            revert(memory[temp15:temp15 + (temp14 + 0x40) - temp15]);
        } else if (arg1 & (0x01 << 0xa0) - 0x01) {
            var var0 = 0x09df;
            var temp0 = memory[0x40:0x60];
            memory[0x40:0x60] = temp0 + 0x60;
            memory[temp0:temp0 + 0x20] = 0x26;
            memory[temp0 + 0x20:temp0 + 0x20 + 0x26] = code[0x0d92:0x0db8];
            memory[0x00:0x20] = arg0 & (0x01 << 0xa0) - 0x01;
            memory[0x20:0x40] = 0x01;
            var var1 = storage[keccak256(memory[0x00:0x40])];
            var var3 = temp0;
            var var2 = arg2;
            var0 = func_0A70(var1, var2, var3);
            var temp1 = (0x01 << 0xa0) - 0x01;
            memory[0x00:0x20] = arg0 & temp1;
            memory[0x20:0x40] = 0x01;
            storage[keccak256(memory[0x00:0x40])] = var0;
            memory[0x00:0x20] = arg1 & temp1;
            var0 = 0x0a14;
            var1 = storage[keccak256(memory[0x00:0x40])];
            var2 = arg2;
            var0 = func_0B07(var1, var2);
            var temp2 = (0x01 << 0xa0) - 0x01;
            var temp3 = arg1 & temp2;
            memory[0x00:0x20] = temp3;
            memory[0x20:0x40] = 0x01;
            storage[keccak256(memory[0x00:0x40])] = var0;
            var temp4 = memory[0x40:0x60];
            memory[temp4:temp4 + 0x20] = arg2;
            var temp5 = memory[0x40:0x60];
            log(memory[temp5:temp5 + temp4 - temp5 + 0x20], [0xddf252ad1be2c89b69c2b068fc378daa952ba7f163c4a11628f55a4df523b3ef, stack[-4] & (0x01 << 0xa0) - 0x01, stack[-3] & (0x01 << 0xa0) - 0x01]);
            return;
        } else {
            var temp6 = memory[0x40:0x60];
            memory[temp6:temp6 + 0x20] = 0x461bcd << 0xe5;
            var temp7 = temp6 + 0x04;
            var temp8 = temp7 + 0x20;
            memory[temp7:temp7 + 0x20] = temp8 - temp7;
            memory[temp8:temp8 + 0x20] = 0x23;
            var temp9 = temp8 + 0x20;
            memory[temp9:temp9 + 0x23] = code[0x0db8:0x0ddb];
            var temp10 = memory[0x40:0x60];
            revert(memory[temp10:temp10 + (temp9 + 0x40) - temp10]);
        }
    }
    
    function func_0A70(var arg0, var arg1, var arg2) returns (var r0) {
        var var0 = 0x00;
        var var1 = arg2;
    
        if (arg1 <= arg0) { return arg0 - arg1; }
    
        var temp0 = memory[0x40:0x60];
        memory[temp0:temp0 + 0x20] = 0x461bcd << 0xe5;
        var temp1 = temp0 + 0x04;
        var var2 = temp1;
        var var3 = var2;
        var temp2 = var3 + 0x20;
        memory[var3:var3 + 0x20] = temp2 - var3;
        var temp3 = var1;
        memory[temp2:temp2 + 0x20] = memory[temp3:temp3 + 0x20];
        var var4 = temp2 + 0x20;
        var var6 = memory[temp3:temp3 + 0x20];
        var var5 = temp3 + 0x20;
        var var7 = var6;
        var var8 = var4;
        var var9 = var5;
        var var10 = 0x00;
    
        if (var10 >= var7) {
        label_0AC4:
            var temp4 = var6;
            var4 = temp4 + var4;
            var5 = temp4 & 0x1f;
        
            if (!var5) {
                var temp5 = memory[0x40:0x60];
                revert(memory[temp5:temp5 + var4 - temp5]);
            } else {
                var temp6 = var5;
                var temp7 = var4 - temp6;
                memory[temp7:temp7 + 0x20] = ~(0x0100 ** (0x20 - temp6) - 0x01) & memory[temp7:temp7 + 0x20];
                var temp8 = memory[0x40:0x60];
                revert(memory[temp8:temp8 + (temp7 + 0x20) - temp8]);
            }
        } else {
        label_0AB5:
            var temp9 = var10;
            memory[temp9 + var8:temp9 + var8 + 0x20] = memory[temp9 + var9:temp9 + var9 + 0x20];
            var10 = temp9 + 0x20;
        
            if (var10 >= var7) { goto label_0AC4; }
            else { goto label_0AB5; }
        }
    }
    
    function func_0B07(var arg0, var arg1) returns (var r0) {
        var var0 = 0x00;
        var temp0 = arg0;
        var var1 = arg1 + temp0;
    
        if (var1 >= temp0) { return var1; }
    
        var temp1 = memory[0x40:0x60];
        memory[temp1:temp1 + 0x20] = 0x461bcd << 0xe5;
        memory[temp1 + 0x04:temp1 + 0x04 + 0x20] = 0x20;
        memory[temp1 + 0x24:temp1 + 0x24 + 0x20] = 0x1b;
        memory[temp1 + 0x44:temp1 + 0x44 + 0x20] = 0x536166654d6174683a206164646974696f6e206f766572666c6f770000000000;
        var temp2 = memory[0x40:0x60];
        revert(memory[temp2:temp2 + temp1 - temp2 + 0x64]);
    }
    
    function func_0C5A(var arg0) {
        if (arg0 & (0x01 << 0xa0) - 0x01) {
            var temp0 = (0x01 << 0xa0) - 0x01;
            var temp1 = arg0;
            log(memory[memory[0x40:0x60]:memory[0x40:0x60] + 0x00], [0x8be0079c531659141344cd1fd0a4f28419497f9722a3daafe3b4186f6b6457e0, storage[0x00] & (0x01 << 0xa0) - 0x01, stack[-1] & (0x01 << 0xa0) - 0x01]);
            storage[0x00] = (temp1 & (0x01 << 0xa0) - 0x01) | (storage[0x00] & ~((0x01 << 0xa0) - 0x01));
            return;
        } else {
            var temp2 = memory[0x40:0x60];
            memory[temp2:temp2 + 0x20] = 0x461bcd << 0xe5;
            var temp3 = temp2 + 0x04;
            var temp4 = temp3 + 0x20;
            memory[temp3:temp3 + 0x20] = temp4 - temp3;
            memory[temp4:temp4 + 0x20] = 0x26;
            var temp5 = temp4 + 0x20;
            memory[temp5:temp5 + 0x26] = code[0x0d44:0x0d6a];
            var temp6 = memory[0x40:0x60];
            revert(memory[temp6:temp6 + (temp5 + 0x40) - temp6]);
        }
    }
}

