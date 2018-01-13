<Type Name="IWithRedisConfiguration" FullName="Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithRedisConfiguration">
  <TypeSignature Language="C#" Value="public interface IWithRedisConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRedisConfiguration" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithRedisConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRedisConfiguration" />
  <TypeSignature Language="F#" Value="type IWithRedisConfiguration = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Redis Cache は、変更を許可する Redis 構成を更新します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutRedisConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithoutRedisConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithoutRedisConfiguration() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithRedisConfiguration.WithoutRedisConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutRedisConfiguration () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutRedisConfiguration : unit -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iWithRedisConfiguration.WithoutRedisConfiguration " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Redis Cache に設定されているすべての構成設定をクリーンアップします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Redis キャッシュの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutRedisConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithoutRedisConfiguration (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithoutRedisConfiguration(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithRedisConfiguration.WithoutRedisConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutRedisConfiguration (key As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutRedisConfiguration : string -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iWithRedisConfiguration.WithoutRedisConfiguration key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">構成名を redis します。</param>
        <summary>
            指定した Redis Cache の構成設定を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Redis キャッシュの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithRedisConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithRedisConfiguration (System.Collections.Generic.IDictionary&lt;string,string&gt; redisConfiguration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithRedisConfiguration(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; redisConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithRedisConfiguration.WithRedisConfiguration(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRedisConfiguration (redisConfiguration As IDictionary(Of String, String)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithRedisConfiguration : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iWithRedisConfiguration.WithRedisConfiguration redisConfiguration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate</ReturnType>
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
        <return>Redis キャッシュの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithRedisConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithRedisConfiguration (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithRedisConfiguration(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithRedisConfiguration.WithRedisConfiguration(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRedisConfiguration (key As String, value As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithRedisConfiguration : string * string -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iWithRedisConfiguration.WithRedisConfiguration (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate</ReturnType>
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
        <return>Redis キャッシュの更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>