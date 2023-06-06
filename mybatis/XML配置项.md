<table border="0" class="table table-striped">
          <thead>
            
<tr class="a">
              
<th>&#x8bbe;&#x7f6e;&#x540d;</th>
              
<th>&#x63cf;&#x8ff0;</th>
              
<th>&#x6709;&#x6548;&#x503c;</th>
              
<th>&#x9ed8;&#x8ba4;&#x503c;</th>
            </tr>
          </thead>
          <tbody>
            
<tr class="b">
              
<td align="left">
                cacheEnabled
              </td>
              
<td>
                &#x5168;&#x5c40;&#x6027;&#x5730;&#x5f00;&#x542f;&#x6216;&#x5173;&#x95ed;&#x6240;&#x6709;&#x6620;&#x5c04;&#x5668;&#x914d;&#x7f6e;&#x6587;&#x4ef6;&#x4e2d;&#x5df2;&#x914d;&#x7f6e;&#x7684;&#x4efb;&#x4f55;&#x7f13;&#x5b58;&#x3002;
              </td>
              
<td>
                true | false
              </td>
              
<td>
                true
              </td>
            </tr>
            
<tr class="a">
              
<td align="left">
                lazyLoadingEnabled
              </td>
              
<td>
                &#x5ef6;&#x8fdf;&#x52a0;&#x8f7d;&#x7684;&#x5168;&#x5c40;&#x5f00;&#x5173;&#x3002;&#x5f53;&#x5f00;&#x542f;&#x65f6;&#xff0c;&#x6240;&#x6709;&#x5173;&#x8054;&#x5bf9;&#x8c61;&#x90fd;&#x4f1a;&#x5ef6;&#x8fdf;&#x52a0;&#x8f7d;&#x3002;
                &#x7279;&#x5b9a;&#x5173;&#x8054;&#x5173;&#x7cfb;&#x4e2d;&#x53ef;&#x901a;&#x8fc7;&#x8bbe;&#x7f6e; <code>fetchType</code>
                &#x5c5e;&#x6027;&#x6765;&#x8986;&#x76d6;&#x8be5;&#x9879;&#x7684;&#x5f00;&#x5173;&#x72b6;&#x6001;&#x3002;
              </td>
              
<td>
                true | false
              </td>
              
<td>
                false
              </td>
            </tr>
            
<tr class="b">
              
<td align="left">
                aggressiveLazyLoading
              </td>
              
<td>
                &#x5f00;&#x542f;&#x65f6;&#xff0c;&#x4efb;&#x4e00;&#x65b9;&#x6cd5;&#x7684;&#x8c03;&#x7528;&#x90fd;&#x4f1a;&#x52a0;&#x8f7d;&#x8be5;&#x5bf9;&#x8c61;&#x7684;&#x6240;&#x6709;&#x5ef6;&#x8fdf;&#x52a0;&#x8f7d;&#x5c5e;&#x6027;&#x3002;
                &#x5426;&#x5219;&#xff0c;&#x6bcf;&#x4e2a;&#x5ef6;&#x8fdf;&#x52a0;&#x8f7d;&#x5c5e;&#x6027;&#x4f1a;&#x6309;&#x9700;&#x52a0;&#x8f7d;&#xff08;&#x53c2;&#x8003; <code>lazyLoadTriggerMethods</code>)&#x3002;
              </td>
              
<td>
                true | false
              </td>
              
<td>
                false &#xff08;&#x5728; 3.4.1 &#x53ca;&#x4e4b;&#x524d;&#x7684;&#x7248;&#x672c;&#x4e2d;&#x9ed8;&#x8ba4;&#x4e3a; true&#xff09;
              </td>
            </tr>
            
<tr class="a">
              
<td align="left">
                multipleResultSetsEnabled
              </td>
              
<td>
                &#x662f;&#x5426;&#x5141;&#x8bb8;&#x5355;&#x4e2a;&#x8bed;&#x53e5;&#x8fd4;&#x56de;&#x591a;&#x7ed3;&#x679c;&#x96c6;&#xff08;&#x9700;&#x8981;&#x6570;&#x636e;&#x5e93;&#x9a71;&#x52a8;&#x652f;&#x6301;&#xff09;&#x3002;
              </td>
              
<td>
                true | false
              </td>
              
<td>
                true
              </td>
            </tr>
            
<tr class="b">
              
<td align="left">
                useColumnLabel
              </td>
              
<td>
                &#x4f7f;&#x7528;&#x5217;&#x6807;&#x7b7e;&#x4ee3;&#x66ff;&#x5217;&#x540d;&#x3002;&#x5b9e;&#x9645;&#x8868;&#x73b0;&#x4f9d;&#x8d56;&#x4e8e;&#x6570;&#x636e;&#x5e93;&#x9a71;&#x52a8;&#xff0c;&#x5177;&#x4f53;&#x53ef;&#x53c2;&#x8003;&#x6570;&#x636e;&#x5e93;&#x9a71;&#x52a8;&#x7684;&#x76f8;&#x5173;&#x6587;&#x6863;&#xff0c;&#x6216;&#x901a;&#x8fc7;&#x5bf9;&#x6bd4;&#x6d4b;&#x8bd5;&#x6765;&#x89c2;&#x5bdf;&#x3002;
              </td>
              
<td>
                true | false
              </td>
              
<td>
                true
              </td>
            </tr>
            
<tr class="a">
              
<td align="left">
                useGeneratedKeys
              </td>
              
<td>
                &#x5141;&#x8bb8; JDBC &#x652f;&#x6301;&#x81ea;&#x52a8;&#x751f;&#x6210;&#x4e3b;&#x952e;&#xff0c;&#x9700;&#x8981;&#x6570;&#x636e;&#x5e93;&#x9a71;&#x52a8;&#x652f;&#x6301;&#x3002;&#x5982;&#x679c;&#x8bbe;&#x7f6e;&#x4e3a;
                true&#xff0c;&#x5c06;&#x5f3a;&#x5236;&#x4f7f;&#x7528;&#x81ea;&#x52a8;&#x751f;&#x6210;&#x4e3b;&#x952e;&#x3002;&#x5c3d;&#x7ba1;&#x4e00;&#x4e9b;&#x6570;&#x636e;&#x5e93;&#x9a71;&#x52a8;&#x4e0d;&#x652f;&#x6301;&#x6b64;&#x7279;&#x6027;&#xff0c;&#x4f46;&#x4ecd;&#x53ef;&#x6b63;&#x5e38;&#x5de5;&#x4f5c;&#xff08;&#x5982; Derby&#xff09;&#x3002;
              </td>
              
<td>
                true | false
              </td>
              
<td>
                False
              </td>
            </tr>
            
<tr class="b">
              
<td align="left">
                autoMappingBehavior
              </td>
              
<td>
                &#x6307;&#x5b9a; MyBatis &#x5e94;&#x5982;&#x4f55;&#x81ea;&#x52a8;&#x6620;&#x5c04;&#x5217;&#x5230;&#x5b57;&#x6bb5;&#x6216;&#x5c5e;&#x6027;&#x3002;
                NONE &#x8868;&#x793a;&#x5173;&#x95ed;&#x81ea;&#x52a8;&#x6620;&#x5c04;&#xff1b;PARTIAL &#x53ea;&#x4f1a;&#x81ea;&#x52a8;&#x6620;&#x5c04;&#x6ca1;&#x6709;&#x5b9a;&#x4e49;&#x5d4c;&#x5957;&#x7ed3;&#x679c;&#x6620;&#x5c04;&#x7684;&#x5b57;&#x6bb5;&#x3002;
                FULL &#x4f1a;&#x81ea;&#x52a8;&#x6620;&#x5c04;&#x4efb;&#x4f55;&#x590d;&#x6742;&#x7684;&#x7ed3;&#x679c;&#x96c6;&#xff08;&#x65e0;&#x8bba;&#x662f;&#x5426;&#x5d4c;&#x5957;&#xff09;&#x3002;
              </td>
              
<td>
                NONE, PARTIAL, FULL
              </td>
              
<td>
                PARTIAL
              </td>
            </tr>
            
<tr class="a">
              
<td align="left">
                autoMappingUnknownColumnBehavior
              </td>
              
<td>
        &#x6307;&#x5b9a;&#x53d1;&#x73b0;&#x81ea;&#x52a8;&#x6620;&#x5c04;&#x76ee;&#x6807;&#x672a;&#x77e5;&#x5217;&#xff08;&#x6216;&#x672a;&#x77e5;&#x5c5e;&#x6027;&#x7c7b;&#x578b;&#xff09;&#x7684;&#x884c;&#x4e3a;&#x3002;
                
<ul>
                  
<li><code>NONE</code>: &#x4e0d;&#x505a;&#x4efb;&#x4f55;&#x53cd;&#x5e94;</li>
                  
<li><code>WARNING</code>:
                  &#x8f93;&#x51fa;&#x8b66;&#x544a;&#x65e5;&#x5fd7;&#xff08;<code>'org.apache.ibatis.session.AutoMappingUnknownColumnBehavior'</code>
                  &#x7684;&#x65e5;&#x5fd7;&#x7b49;&#x7ea7;&#x5fc5;&#x987b;&#x8bbe;&#x7f6e;&#x4e3a; <code>WARN</code>&#xff09;</li>
                  
<li><code>FAILING</code>: &#x6620;&#x5c04;&#x5931;&#x8d25; (&#x629b;&#x51fa; <code>SqlSessionException</code>)</li>
                </ul>
              </td>
              
<td>
                NONE, WARNING, FAILING
              </td>
              
<td>
                NONE
              </td>
            </tr>
            
<tr class="b">
              
<td align="left">
                defaultExecutorType
              </td>
              
<td>
                &#x914d;&#x7f6e;&#x9ed8;&#x8ba4;&#x7684;&#x6267;&#x884c;&#x5668;&#x3002;SIMPLE &#x5c31;&#x662f;&#x666e;&#x901a;&#x7684;&#x6267;&#x884c;&#x5668;&#xff1b;REUSE &#x6267;&#x884c;&#x5668;&#x4f1a;&#x91cd;&#x7528;&#x9884;&#x5904;&#x7406;&#x8bed;&#x53e5;&#xff08;PreparedStatement&#xff09;&#xff1b;
                BATCH &#x6267;&#x884c;&#x5668;&#x4e0d;&#x4ec5;&#x91cd;&#x7528;&#x8bed;&#x53e5;&#x8fd8;&#x4f1a;&#x6267;&#x884c;&#x6279;&#x91cf;&#x66f4;&#x65b0;&#x3002;
              </td>
              
<td>
                SIMPLE
                REUSE
                BATCH
              </td>
              
<td>
                SIMPLE
              </td>
            </tr>
            
<tr class="a">
              
<td align="left">
                defaultStatementTimeout
              </td>
              
<td>
                &#x8bbe;&#x7f6e;&#x8d85;&#x65f6;&#x65f6;&#x95f4;&#xff0c;&#x5b83;&#x51b3;&#x5b9a;&#x6570;&#x636e;&#x5e93;&#x9a71;&#x52a8;&#x7b49;&#x5f85;&#x6570;&#x636e;&#x5e93;&#x54cd;&#x5e94;&#x7684;&#x79d2;&#x6570;&#x3002;
              </td>
              
<td>
                &#x4efb;&#x610f;&#x6b63;&#x6574;&#x6570;
              </td>
              
<td>
                &#x672a;&#x8bbe;&#x7f6e; (null)
              </td>
            </tr>
            
<tr class="b">
              
<td align="left">
                defaultFetchSize
              </td>
              
<td>
                &#x4e3a;&#x9a71;&#x52a8;&#x7684;&#x7ed3;&#x679c;&#x96c6;&#x83b7;&#x53d6;&#x6570;&#x91cf;&#xff08;fetchSize&#xff09;&#x8bbe;&#x7f6e;&#x4e00;&#x4e2a;&#x5efa;&#x8bae;&#x503c;&#x3002;&#x6b64;&#x53c2;&#x6570;&#x53ea;&#x53ef;&#x4ee5;&#x5728;&#x67e5;&#x8be2;&#x8bbe;&#x7f6e;&#x4e2d;&#x88ab;&#x8986;&#x76d6;&#x3002;
              </td>
              
<td>
                &#x4efb;&#x610f;&#x6b63;&#x6574;&#x6570;
              </td>
              
<td>
                &#x672a;&#x8bbe;&#x7f6e; (null)
              </td>
            </tr>
            
<tr class="a">
              
<td align="left">
                defaultResultSetType
              </td>
              
<td>
                &#x6307;&#x5b9a;&#x8bed;&#x53e5;&#x9ed8;&#x8ba4;&#x7684;&#x6eda;&#x52a8;&#x7b56;&#x7565;&#x3002;&#xff08;&#x65b0;&#x589e;&#x4e8e; 3.5.2&#xff09;
              </td>
              
<td>
                FORWARD_ONLY | SCROLL_SENSITIVE | SCROLL_INSENSITIVE | DEFAULT&#xff08;&#x7b49;&#x540c;&#x4e8e;&#x672a;&#x8bbe;&#x7f6e;&#xff09;
              </td>
              
<td>
                &#x672a;&#x8bbe;&#x7f6e; (null)
              </td>
            </tr>
            
<tr class="b">
              
<td align="left">
                safeRowBoundsEnabled
              </td>
              
<td>
                &#x662f;&#x5426;&#x5141;&#x8bb8;&#x5728;&#x5d4c;&#x5957;&#x8bed;&#x53e5;&#x4e2d;&#x4f7f;&#x7528;&#x5206;&#x9875;&#xff08;RowBounds&#xff09;&#x3002;&#x5982;&#x679c;&#x5141;&#x8bb8;&#x4f7f;&#x7528;&#x5219;&#x8bbe;&#x7f6e;&#x4e3a; false&#x3002;
              </td>
              
<td>
                true | false
              </td>
              
<td>
                False
              </td>
            </tr>
            
<tr class="a">
              
<td align="left">
                safeResultHandlerEnabled
              </td>
              
<td>
                &#x662f;&#x5426;&#x5141;&#x8bb8;&#x5728;&#x5d4c;&#x5957;&#x8bed;&#x53e5;&#x4e2d;&#x4f7f;&#x7528;&#x7ed3;&#x679c;&#x5904;&#x7406;&#x5668;&#xff08;ResultHandler&#xff09;&#x3002;&#x5982;&#x679c;&#x5141;&#x8bb8;&#x4f7f;&#x7528;&#x5219;&#x8bbe;&#x7f6e;&#x4e3a; false&#x3002;
              </td>
              
<td>
                true | false
              </td>
              
<td>
                True
              </td>
            </tr>
            
<tr class="b">
              
<td align="left">
                mapUnderscoreToCamelCase
              </td>
              
<td>
                &#x662f;&#x5426;&#x5f00;&#x542f;&#x9a7c;&#x5cf0;&#x547d;&#x540d;&#x81ea;&#x52a8;&#x6620;&#x5c04;&#xff0c;&#x5373;&#x4ece;&#x7ecf;&#x5178;&#x6570;&#x636e;&#x5e93;&#x5217;&#x540d;
                A_COLUMN &#x6620;&#x5c04;&#x5230;&#x7ecf;&#x5178; Java &#x5c5e;&#x6027;&#x540d; aColumn&#x3002;
              </td>
              
<td>
                true | false
              </td>
              
<td>
                False
              </td>
            </tr>
            
<tr class="a">
              
<td align="left">
                localCacheScope
              </td>
              
<td>
                MyBatis &#x5229;&#x7528;&#x672c;&#x5730;&#x7f13;&#x5b58;&#x673a;&#x5236;&#xff08;Local Cache&#xff09;&#x9632;&#x6b62;&#x5faa;&#x73af;&#x5f15;&#x7528;&#x548c;&#x52a0;&#x901f;&#x91cd;&#x590d;&#x7684;&#x5d4c;&#x5957;&#x67e5;&#x8be2;&#x3002;
                &#x9ed8;&#x8ba4;&#x503c;&#x4e3a; SESSION&#xff0c;&#x4f1a;&#x7f13;&#x5b58;&#x4e00;&#x4e2a;&#x4f1a;&#x8bdd;&#x4e2d;&#x6267;&#x884c;&#x7684;&#x6240;&#x6709;&#x67e5;&#x8be2;&#x3002;
                &#x82e5;&#x8bbe;&#x7f6e;&#x503c;&#x4e3a; STATEMENT&#xff0c;&#x672c;&#x5730;&#x7f13;&#x5b58;&#x5c06;&#x4ec5;&#x7528;&#x4e8e;&#x6267;&#x884c;&#x8bed;&#x53e5;&#xff0c;&#x5bf9;&#x76f8;&#x540c; SqlSession &#x7684;&#x4e0d;&#x540c;&#x67e5;&#x8be2;&#x5c06;&#x4e0d;&#x4f1a;&#x8fdb;&#x884c;&#x7f13;&#x5b58;&#x3002;
              </td>
              
<td>
                SESSION | STATEMENT
              </td>
              
<td>
                SESSION
              </td>
            </tr>
            
<tr class="b">
              
<td align="left">
                jdbcTypeForNull
              </td>
              
<td>
                &#x5f53;&#x6ca1;&#x6709;&#x4e3a;&#x53c2;&#x6570;&#x6307;&#x5b9a;&#x7279;&#x5b9a;&#x7684; JDBC &#x7c7b;&#x578b;&#x65f6;&#xff0c;&#x7a7a;&#x503c;&#x7684;&#x9ed8;&#x8ba4; JDBC &#x7c7b;&#x578b;&#x3002;
                &#x67d0;&#x4e9b;&#x6570;&#x636e;&#x5e93;&#x9a71;&#x52a8;&#x9700;&#x8981;&#x6307;&#x5b9a;&#x5217;&#x7684; JDBC &#x7c7b;&#x578b;&#xff0c;&#x591a;&#x6570;&#x60c5;&#x51b5;&#x76f4;&#x63a5;&#x7528;&#x4e00;&#x822c;&#x7c7b;&#x578b;&#x5373;&#x53ef;&#xff0c;&#x6bd4;&#x5982; NULL&#x3001;VARCHAR &#x6216; OTHER&#x3002;
              </td>
              
<td>
                JdbcType &#x5e38;&#x91cf;&#xff0c;&#x5e38;&#x7528;&#x503c;&#xff1a;NULL&#x3001;VARCHAR &#x6216; OTHER&#x3002;
              </td>
              
<td>
                OTHER
              </td>
            </tr>
            
<tr class="a">
              
<td align="left">
                lazyLoadTriggerMethods
              </td>
              
<td>
                &#x6307;&#x5b9a;&#x5bf9;&#x8c61;&#x7684;&#x54ea;&#x4e9b;&#x65b9;&#x6cd5;&#x89e6;&#x53d1;&#x4e00;&#x6b21;&#x5ef6;&#x8fdf;&#x52a0;&#x8f7d;&#x3002;
              </td>
              
<td>
                &#x7528;&#x9017;&#x53f7;&#x5206;&#x9694;&#x7684;&#x65b9;&#x6cd5;&#x5217;&#x8868;&#x3002;
              </td>
              
<td>
                equals,clone,hashCode,toString
              </td>
            </tr>
            
<tr class="b">
              
<td align="left">
                defaultScriptingLanguage
              </td>
              
<td>
                &#x6307;&#x5b9a;&#x52a8;&#x6001; SQL &#x751f;&#x6210;&#x4f7f;&#x7528;&#x7684;&#x9ed8;&#x8ba4;&#x811a;&#x672c;&#x8bed;&#x8a00;&#x3002;
              </td>
              
<td>
                &#x4e00;&#x4e2a;&#x7c7b;&#x578b;&#x522b;&#x540d;&#x6216;&#x5168;&#x9650;&#x5b9a;&#x7c7b;&#x540d;&#x3002;
              </td>
              
<td>
                org.apache.ibatis.scripting.xmltags.XMLLanguageDriver
              </td>
            </tr>
            
<tr class="a">
              
<td align="left">
                defaultEnumTypeHandler
              </td>
              
<td>
                &#x6307;&#x5b9a; Enum &#x4f7f;&#x7528;&#x7684;&#x9ed8;&#x8ba4; <code>TypeHandler</code> &#x3002;&#xff08;&#x65b0;&#x589e;&#x4e8e; 3.4.5&#xff09;
              </td>
              
<td>
                &#x4e00;&#x4e2a;&#x7c7b;&#x578b;&#x522b;&#x540d;&#x6216;&#x5168;&#x9650;&#x5b9a;&#x7c7b;&#x540d;&#x3002;
              </td>
              
<td>
                org.apache.ibatis.type.EnumTypeHandler
              </td>
            </tr>
            
<tr class="b">
              
<td align="left">
                callSettersOnNulls
              </td>
              
<td>
                &#x6307;&#x5b9a;&#x5f53;&#x7ed3;&#x679c;&#x96c6;&#x4e2d;&#x503c;&#x4e3a; null &#x7684;&#x65f6;&#x5019;&#x662f;&#x5426;&#x8c03;&#x7528;&#x6620;&#x5c04;&#x5bf9;&#x8c61;&#x7684; setter&#xff08;map
                &#x5bf9;&#x8c61;&#x65f6;&#x4e3a; put&#xff09;&#x65b9;&#x6cd5;&#xff0c;&#x8fd9;&#x5728;&#x4f9d;&#x8d56;&#x4e8e; Map.keySet() &#x6216; null
                &#x503c;&#x8fdb;&#x884c;&#x521d;&#x59cb;&#x5316;&#x65f6;&#x6bd4;&#x8f83;&#x6709;&#x7528;&#x3002;&#x6ce8;&#x610f;&#x57fa;&#x672c;&#x7c7b;&#x578b;&#xff08;int&#x3001;boolean &#x7b49;&#xff09;&#x662f;&#x4e0d;&#x80fd;&#x8bbe;&#x7f6e;&#x6210; null &#x7684;&#x3002;
              </td>
              
<td>
                true | false
              </td>
              
<td>
                false
              </td>
            </tr>
            
<tr class="a">
              
<td align="left">
                returnInstanceForEmptyRow
              </td>
              
<td>
        &#x5f53;&#x8fd4;&#x56de;&#x884c;&#x7684;&#x6240;&#x6709;&#x5217;&#x90fd;&#x662f;&#x7a7a;&#x65f6;&#xff0c;MyBatis&#x9ed8;&#x8ba4;&#x8fd4;&#x56de; <code>null</code>&#x3002;
        &#x5f53;&#x5f00;&#x542f;&#x8fd9;&#x4e2a;&#x8bbe;&#x7f6e;&#x65f6;&#xff0c;MyBatis&#x4f1a;&#x8fd4;&#x56de;&#x4e00;&#x4e2a;&#x7a7a;&#x5b9e;&#x4f8b;&#x3002;
        &#x8bf7;&#x6ce8;&#x610f;&#xff0c;&#x5b83;&#x4e5f;&#x9002;&#x7528;&#x4e8e;&#x5d4c;&#x5957;&#x7684;&#x7ed3;&#x679c;&#x96c6;&#xff08;&#x5982;&#x96c6;&#x5408;&#x6216;&#x5173;&#x8054;&#xff09;&#x3002;&#xff08;&#x65b0;&#x589e;&#x4e8e; 3.4.2&#xff09;
              </td>
              
<td>
                true | false
              </td>
              
<td>
                false
              </td>
            </tr>
            
<tr class="b">
              
<td align="left">
                logPrefix
              </td>
              
<td>
                &#x6307;&#x5b9a; MyBatis &#x589e;&#x52a0;&#x5230;&#x65e5;&#x5fd7;&#x540d;&#x79f0;&#x7684;&#x524d;&#x7f00;&#x3002;
              </td>
              
<td>
                &#x4efb;&#x4f55;&#x5b57;&#x7b26;&#x4e32;
              </td>
              
<td>
                &#x672a;&#x8bbe;&#x7f6e;
              </td>
            </tr>
            
<tr class="a">
              
<td align="left">
                logImpl
              </td>
              
<td>
                &#x6307;&#x5b9a; MyBatis &#x6240;&#x7528;&#x65e5;&#x5fd7;&#x7684;&#x5177;&#x4f53;&#x5b9e;&#x73b0;&#xff0c;&#x672a;&#x6307;&#x5b9a;&#x65f6;&#x5c06;&#x81ea;&#x52a8;&#x67e5;&#x627e;&#x3002;
              </td>
              
<td>
                SLF4J | LOG4J&#xff08;3.5.9 &#x8d77;&#x5e9f;&#x5f03;&#xff09; | LOG4J2 | JDK_LOGGING | COMMONS_LOGGING | STDOUT_LOGGING | NO_LOGGING
              </td>
              
<td>
                &#x672a;&#x8bbe;&#x7f6e;
              </td>
            </tr>
            
<tr class="b">
              
<td align="left">
                proxyFactory
              </td>
              
<td>
                &#x6307;&#x5b9a; Mybatis &#x521b;&#x5efa;&#x53ef;&#x5ef6;&#x8fdf;&#x52a0;&#x8f7d;&#x5bf9;&#x8c61;&#x6240;&#x7528;&#x5230;&#x7684;&#x4ee3;&#x7406;&#x5de5;&#x5177;&#x3002;
              </td>
              
<td>
                CGLIB &#xff08;3.5.10 &#x8d77;&#x5e9f;&#x5f03;&#xff09; | JAVASSIST
              </td>
              
<td>
                JAVASSIST &#xff08;MyBatis 3.3 &#x4ee5;&#x4e0a;&#xff09;
              </td>
            </tr>
            
<tr class="a">
              
<td align="left">
                vfsImpl
              </td>
              
<td>
                &#x6307;&#x5b9a; VFS &#x7684;&#x5b9e;&#x73b0;
              </td>
              
<td>
                &#x81ea;&#x5b9a;&#x4e49; VFS &#x7684;&#x5b9e;&#x73b0;&#x7684;&#x7c7b;&#x5168;&#x9650;&#x5b9a;&#x540d;&#xff0c;&#x4ee5;&#x9017;&#x53f7;&#x5206;&#x9694;&#x3002;
              </td>
              
<td>
                &#x672a;&#x8bbe;&#x7f6e;
              </td>
            </tr>
            
<tr class="b">
              
<td align="left">
                useActualParamName
              </td>
              
<td>
                &#x5141;&#x8bb8;&#x4f7f;&#x7528;&#x65b9;&#x6cd5;&#x7b7e;&#x540d;&#x4e2d;&#x7684;&#x540d;&#x79f0;&#x4f5c;&#x4e3a;&#x8bed;&#x53e5;&#x53c2;&#x6570;&#x540d;&#x79f0;&#x3002;
            &#x4e3a;&#x4e86;&#x4f7f;&#x7528;&#x8be5;&#x7279;&#x6027;&#xff0c;&#x4f60;&#x7684;&#x9879;&#x76ee;&#x5fc5;&#x987b;&#x91c7;&#x7528; Java 8 &#x7f16;&#x8bd1;&#xff0c;&#x5e76;&#x4e14;&#x52a0;&#x4e0a; <code>-parameters</code> &#x9009;&#x9879;&#x3002;&#xff08;&#x65b0;&#x589e;&#x4e8e; 3.4.1&#xff09;
              </td>
              
<td>
                true | false
              </td>
              
<td>
                true
              </td>
            </tr>
            
<tr class="a">
              
<td align="left">
                configurationFactory
              </td>
              
<td>
                &#x6307;&#x5b9a;&#x4e00;&#x4e2a;&#x63d0;&#x4f9b; <code>Configuration</code> &#x5b9e;&#x4f8b;&#x7684;&#x7c7b;&#x3002;
                &#x8fd9;&#x4e2a;&#x88ab;&#x8fd4;&#x56de;&#x7684; Configuration &#x5b9e;&#x4f8b;&#x7528;&#x6765;&#x52a0;&#x8f7d;&#x88ab;&#x53cd;&#x5e8f;&#x5217;&#x5316;&#x5bf9;&#x8c61;&#x7684;&#x5ef6;&#x8fdf;&#x52a0;&#x8f7d;&#x5c5e;&#x6027;&#x503c;&#x3002;
                &#x8fd9;&#x4e2a;&#x7c7b;&#x5fc5;&#x987b;&#x5305;&#x542b;&#x4e00;&#x4e2a;&#x7b7e;&#x540d;&#x4e3a;<code>static Configuration getConfiguration()</code> &#x7684;&#x65b9;&#x6cd5;&#x3002;&#xff08;&#x65b0;&#x589e;&#x4e8e; 3.2.3&#xff09;
              </td>
              
<td>
                &#x4e00;&#x4e2a;&#x7c7b;&#x578b;&#x522b;&#x540d;&#x6216;&#x5b8c;&#x5168;&#x9650;&#x5b9a;&#x7c7b;&#x540d;&#x3002;
              </td>
              
<td>
                &#x672a;&#x8bbe;&#x7f6e;
              </td>
            </tr>
            
<tr class="b">
              
<td align="left">
                shrinkWhitespacesInSql
              </td>
              
<td>
                &#x4ece;SQL&#x4e2d;&#x5220;&#x9664;&#x591a;&#x4f59;&#x7684;&#x7a7a;&#x683c;&#x5b57;&#x7b26;&#x3002;&#x8bf7;&#x6ce8;&#x610f;&#xff0c;&#x8fd9;&#x4e5f;&#x4f1a;&#x5f71;&#x54cd;SQL&#x4e2d;&#x7684;&#x6587;&#x5b57;&#x5b57;&#x7b26;&#x4e32;&#x3002; (&#x65b0;&#x589e;&#x4e8e; 3.5.5)
              </td>
              
<td>
                true | false
              </td>
              
<td>
                false
              </td>
            </tr>
            
<tr class="a">
              
<td align="left">
                defaultSqlProviderType
              </td>
              
<td>
                &#x6307;&#x5b9a;&#x4e00;&#x4e2a;&#x62e5;&#x6709; provider &#x65b9;&#x6cd5;&#x7684; sql provider &#x7c7b; &#xff08;&#x65b0;&#x589e;&#x4e8e; 3.5.6&#xff09;.
                &#x8fd9;&#x4e2a;&#x7c7b;&#x9002;&#x7528;&#x4e8e;&#x6307;&#x5b9a; sql provider &#x6ce8;&#x89e3;&#x4e0a;&#x7684;<code>type</code>&#xff08;&#x6216; <code>value</code>&#xff09; &#x5c5e;&#x6027;&#xff08;&#x5f53;&#x8fd9;&#x4e9b;&#x5c5e;&#x6027;&#x5728;&#x6ce8;&#x89e3;&#x4e2d;&#x88ab;&#x5ffd;&#x7565;&#x65f6;&#xff09;&#x3002; (e.g. <code>@SelectProvider</code>)
              </td>
              
<td>
                &#x7c7b;&#x578b;&#x522b;&#x540d;&#x6216;&#x8005;&#x5168;&#x9650;&#x5b9a;&#x540d;
              </td>
              
<td>
                &#x672a;&#x8bbe;&#x7f6e;
              </td>
            </tr>
            
<tr class="b">
              
<td align="left">
                nullableOnForEach
              </td>
              
<td>
                &#x4e3a; 'foreach' &#x6807;&#x7b7e;&#x7684; 'nullable' &#x5c5e;&#x6027;&#x6307;&#x5b9a;&#x9ed8;&#x8ba4;&#x503c;&#x3002;&#xff08;&#x65b0;&#x589e;&#x4e8e; 3.5.9&#xff09;
              </td>
              
<td>
                true | false
              </td>
              
<td>
                false
              </td>
            </tr>
            
<tr class="a">
              
<td align="left">
                argNameBasedConstructorAutoMapping
              </td>
              
<td>
               &#x5f53;&#x5e94;&#x7528;&#x6784;&#x9020;&#x5668;&#x81ea;&#x52a8;&#x6620;&#x5c04;&#x65f6;&#xff0c;&#x53c2;&#x6570;&#x540d;&#x79f0;&#x88ab;&#x7528;&#x6765;&#x641c;&#x7d22;&#x8981;&#x6620;&#x5c04;&#x7684;&#x5217;&#xff0c;&#x800c;&#x4e0d;&#x518d;&#x4f9d;&#x8d56;&#x5217;&#x7684;&#x987a;&#x5e8f;&#x3002;&#xff08;&#x65b0;&#x589e;&#x4e8e; 3.5.10&#xff09;
              </td>
              
<td>
                true | false
              </td>
              
<td>
                false
              </td>
            </tr>
          </tbody>
        </table>
        