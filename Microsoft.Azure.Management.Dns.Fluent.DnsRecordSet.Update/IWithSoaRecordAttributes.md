<Type Name="IWithSoaRecordAttributes" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithSoaRecordAttributes">
  <TypeSignature Language="C#" Value="public interface IWithSoaRecordAttributes" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSoaRecordAttributes" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithSoaRecordAttributes" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSoaRecordAttributes" />
  <TypeSignature Language="F#" Value="type IWithSoaRecordAttributes = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            その属性を更新できるように SOA レコードの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithEmailServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithEmailServer (string emailServerHostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithEmailServer(string emailServerHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithSoaRecordAttributes.WithEmailServer(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithEmailServer (emailServerHostName As String) As IUpdateSoaRecord" />
      <MemberSignature Language="F#" Value="abstract member WithEmailServer : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord" Usage="iWithSoaRecordAttributes.WithEmailServer emailServerHostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="emailServerHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="emailServerHostName">電子メール サーバーです。</param>
        <summary>
            SOA レコードに関連付けられている電子メール サーバーを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>レコードの次のステージでは、更新プログラムを設定します。</return>
      </Docs>
    </Member>
    <Member MemberName="WithExpireTimeInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithExpireTimeInSeconds (long expireTimeInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithExpireTimeInSeconds(int64 expireTimeInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithSoaRecordAttributes.WithExpireTimeInSeconds(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExpireTimeInSeconds (expireTimeInSeconds As Long) As IUpdateSoaRecord" />
      <MemberSignature Language="F#" Value="abstract member WithExpireTimeInSeconds : int64 -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord" Usage="iWithSoaRecordAttributes.WithExpireTimeInSeconds expireTimeInSeconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="expireTimeInSeconds" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="expireTimeInSeconds">秒単位で有効期限の時刻。</param>
        <summary>
            セカンダリ ネーム サーバーは、キャッシュされたゾーン ファイルとして扱います有効な名前のプライマリ サーバーに接続できないときに秒単位で時間を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>レコードの次のステージでは、更新プログラムを設定します。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNegativeResponseCachingTimeToLiveInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithNegativeResponseCachingTimeToLiveInSeconds (long negativeCachingTimeToLive);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithNegativeResponseCachingTimeToLiveInSeconds(int64 negativeCachingTimeToLive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithSoaRecordAttributes.WithNegativeResponseCachingTimeToLiveInSeconds(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNegativeResponseCachingTimeToLiveInSeconds (negativeCachingTimeToLive As Long) As IUpdateSoaRecord" />
      <MemberSignature Language="F#" Value="abstract member WithNegativeResponseCachingTimeToLiveInSeconds : int64 -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord" Usage="iWithSoaRecordAttributes.WithNegativeResponseCachingTimeToLiveInSeconds negativeCachingTimeToLive" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="negativeCachingTimeToLive" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="negativeCachingTimeToLive">否定応答がキャッシュされているために TTL です。</param>
        <summary>
            任意の名前のサーバーまたは競合回避モジュールが否定応答をキャッシュする秒単位で時間を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>レコードの次のステージでは、更新プログラムを設定します。</return>
      </Docs>
    </Member>
    <Member MemberName="WithRefreshTimeInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithRefreshTimeInSeconds (long refreshTimeInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithRefreshTimeInSeconds(int64 refreshTimeInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithSoaRecordAttributes.WithRefreshTimeInSeconds(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRefreshTimeInSeconds (refreshTimeInSeconds As Long) As IUpdateSoaRecord" />
      <MemberSignature Language="F#" Value="abstract member WithRefreshTimeInSeconds : int64 -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord" Usage="iWithSoaRecordAttributes.WithRefreshTimeInSeconds refreshTimeInSeconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="refreshTimeInSeconds" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="refreshTimeInSeconds">更新時間を秒単位で。</param>
        <summary>
            セカンダリ ネーム サーバーが接続しようとする前に待機する秒単位で時間を指定します、プライマリ名前サーバー、ゾーン ファイルを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>レコードの次のステージでは、更新プログラムを設定します。</return>
      </Docs>
    </Member>
    <Member MemberName="WithRetryTimeInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithRetryTimeInSeconds (long refreshTimeInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithRetryTimeInSeconds(int64 refreshTimeInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithSoaRecordAttributes.WithRetryTimeInSeconds(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRetryTimeInSeconds (refreshTimeInSeconds As Long) As IUpdateSoaRecord" />
      <MemberSignature Language="F#" Value="abstract member WithRetryTimeInSeconds : int64 -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord" Usage="iWithSoaRecordAttributes.WithRetryTimeInSeconds refreshTimeInSeconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="refreshTimeInSeconds" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="refreshTimeInSeconds">秒単位で再試行時間。</param>
        <summary>
            セカンダリのネーム サーバーがゾーン ファイルの更新プログラムの確認に失敗した後にもう一度プライマリ ネーム サーバーに接続する前に待機する秒単位で時間を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>レコードの次のステージでは、更新プログラムを設定します。</return>
      </Docs>
    </Member>
    <Member MemberName="WithSerialNumber">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithSerialNumber (long serialNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithSerialNumber(int64 serialNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithSoaRecordAttributes.WithSerialNumber(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSerialNumber (serialNumber As Long) As IUpdateSoaRecord" />
      <MemberSignature Language="F#" Value="abstract member WithSerialNumber : int64 -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord" Usage="iWithSoaRecordAttributes.WithSerialNumber serialNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serialNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="serialNumber">シリアル番号。</param>
        <summary>
            ゾーン ファイルのシリアル番号を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>レコードの次のステージでは、更新プログラムを設定します。</return>
      </Docs>
    </Member>
  </Members>
</Type>