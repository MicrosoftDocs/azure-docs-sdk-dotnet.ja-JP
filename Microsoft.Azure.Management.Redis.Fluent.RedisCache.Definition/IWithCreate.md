<Type Name="IWithCreate" FullName="Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate">
  <TypeSignature Language="C#" Value="public interface IWithCreate : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCreate implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCreate&#xA;Implements ICreatable(Of IRedisCache), IDefinitionWithTags(Of IWithCreate)" />
  <TypeSignature Language="F#" Value="type IWithCreate = interface&#xA;    interface ICreatable&lt;IRedisCache&gt;&#xA;    interface IIndexable&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            クラウドを指定する省略可能な追加の入力を公開する新しい Redis Cache を作成するための十分な入力で Redis Cache 定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNonSslPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithNonSslPort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithNonSslPort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate.WithNonSslPort" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNonSslPort () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNonSslPort : unit -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" Usage="iWithCreate.WithNonSslPort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ポート (6379 を) の Redis サーバーの非 ssl を有効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Redis Cache の定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithRedisConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithRedisConfiguration (System.Collections.Generic.IDictionary&lt;string,string&gt; redisConfiguration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithRedisConfiguration(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; redisConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate.WithRedisConfiguration(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRedisConfiguration (redisConfiguration As IDictionary(Of String, String)) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithRedisConfiguration : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" Usage="iWithCreate.WithRedisConfiguration redisConfiguration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="redisConfiguration" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="redisConfiguration">構成名でインデックス付けされたマップとして Redis Cache の構成。</param>
        <summary>
            すべては Redis の設定です。 いくつかの可能なキー: rdb バックアップ-有効になっている、rdb ストレージ接続文字列、rdb のバックアップの頻度、maxmemory デルタ、maxmemory ポリシー、通知 keyspace イベント、maxmemory サンプル slowlog-ログ-低速の設定よりも、slowlog max-len リスト max-ziplist エントリ、リスト max-ziplist 値、ハッシュの最大-ziplist-エントリ、ハッシュ max-ziplist 値、- 最大値-intset-エントリ、zset 最大 ziplist エントリ、zset 最大 ziplist-値などです。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Redis Cache の定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithRedisConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithRedisConfiguration (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithRedisConfiguration(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate.WithRedisConfiguration(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRedisConfiguration (key As String, value As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithRedisConfiguration : string * string -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" Usage="iWithCreate.WithRedisConfiguration (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">構成名を redis します。</param>
        <param name="value">構成値を redis します。</param>
        <summary>
            Redis の設定を指定します。
            rdb バックアップ-有効になっている、rdb ストレージ接続文字列、rdb のバックアップの頻度、maxmemory デルタ、maxmemory ポリシー、通知 keyspace イベント、maxmemory サンプル slowlog-ログ-低速の設定よりも、slowlog max-len リスト max-ziplist エントリ、リスト max-ziplist 値、ハッシュの最大-ziplist-エントリ、ハッシュ max-ziplist 値、- 最大値-intset-エントリ、zset 最大 ziplist エントリ、zset 最大 ziplist-値などです。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Redis Cache の定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithStaticIP">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithStaticIP (string staticIP);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithStaticIP(string staticIP) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate.WithStaticIP(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStaticIP (staticIP As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithStaticIP : string -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" Usage="iWithCreate.WithStaticIP staticIP" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="staticIP" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="staticIP">静的 IP 設定する値。</param>
        <summary>
            Redis Cache の静的 IP を設定します。 既存の Azure 仮想ネットワーク内 Redis Cache を展開するときに必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Redis Cache の定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithSubnet (Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId network, string subnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithSubnet(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId network, string subnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate.WithSubnet(Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSubnet (network As IHasId, subnetName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithSubnet : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId * string -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" Usage="iWithCreate.WithSubnet (network, subnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId" />
        <Parameter Name="subnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="network">ネットワークのオブジェクトのインスタンス。</param>
        <param name="subnetName">サブネットの名前。</param>
        <summary>
            Redis Cache のこのインスタンスに指定されたサブネットを割り当てます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Redis Cache の定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>