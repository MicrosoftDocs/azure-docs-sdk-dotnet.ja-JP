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
            <span data-ttu-id="451f4-101">その属性を更新できるように SOA レコードの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="451f4-101">The stage of the SOA record definition allowing to update its attributes.</span></span>
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
        <param name="emailServerHostName"><span data-ttu-id="451f4-102">電子メール サーバーです。</span><span class="sxs-lookup"><span data-stu-id="451f4-102">The email server.</span></span></param>
        <summary>
            <span data-ttu-id="451f4-103">SOA レコードに関連付けられている電子メール サーバーを指定します。</span><span class="sxs-lookup"><span data-stu-id="451f4-103">Specifies the email server associated with the SOA record.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="451f4-104">レコードの次のステージでは、更新プログラムを設定します。</span><span class="sxs-lookup"><span data-stu-id="451f4-104">The next stage of the record set update.</span></span></return>
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
        <param name="expireTimeInSeconds"><span data-ttu-id="451f4-105">秒単位で有効期限の時刻。</span><span class="sxs-lookup"><span data-stu-id="451f4-105">The expire time in seconds.</span></span></param>
        <summary>
            <span data-ttu-id="451f4-106">セカンダリ ネーム サーバーは、キャッシュされたゾーン ファイルとして扱います有効な名前のプライマリ サーバーに接続できないときに秒単位で時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="451f4-106">Specifies the time in seconds that a secondary name server will treat its cached zone file as valid when the primary name server cannot be contacted.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="451f4-107">レコードの次のステージでは、更新プログラムを設定します。</span><span class="sxs-lookup"><span data-stu-id="451f4-107">The next stage of the record set update.</span></span></return>
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
        <param name="negativeCachingTimeToLive"><span data-ttu-id="451f4-108">否定応答がキャッシュされているために TTL です。</span><span class="sxs-lookup"><span data-stu-id="451f4-108">The TTL for cached negative response.</span></span></param>
        <summary>
            <span data-ttu-id="451f4-109">任意の名前のサーバーまたは競合回避モジュールが否定応答をキャッシュする秒単位で時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="451f4-109">Specifies the time in seconds that any name server or resolver should cache a negative response.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="451f4-110">レコードの次のステージでは、更新プログラムを設定します。</span><span class="sxs-lookup"><span data-stu-id="451f4-110">The next stage of the record set update.</span></span></return>
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
        <param name="refreshTimeInSeconds"><span data-ttu-id="451f4-111">更新時間を秒単位で。</span><span class="sxs-lookup"><span data-stu-id="451f4-111">The refresh time in seconds.</span></span></param>
        <summary>
            <span data-ttu-id="451f4-112">セカンダリ ネーム サーバーが接続しようとする前に待機する秒単位で時間を指定します、プライマリ名前サーバー、ゾーン ファイルを更新します。</span><span class="sxs-lookup"><span data-stu-id="451f4-112">Specifies time in seconds that a secondary name server should wait before trying to contact the the primary name server for a zone file update.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="451f4-113">レコードの次のステージでは、更新プログラムを設定します。</span><span class="sxs-lookup"><span data-stu-id="451f4-113">The next stage of the record set update.</span></span></return>
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
        <param name="refreshTimeInSeconds"><span data-ttu-id="451f4-114">秒単位で再試行時間。</span><span class="sxs-lookup"><span data-stu-id="451f4-114">The retry time in seconds.</span></span></param>
        <summary>
            <span data-ttu-id="451f4-115">セカンダリのネーム サーバーがゾーン ファイルの更新プログラムの確認に失敗した後にもう一度プライマリ ネーム サーバーに接続する前に待機する秒単位で時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="451f4-115">Specifies the time in seconds that a secondary name server should wait before trying to contact the primary name server again after a failed attempt to check for a zone file update.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="451f4-116">レコードの次のステージでは、更新プログラムを設定します。</span><span class="sxs-lookup"><span data-stu-id="451f4-116">The next stage of the record set update.</span></span></return>
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
        <param name="serialNumber"><span data-ttu-id="451f4-117">シリアル番号。</span><span class="sxs-lookup"><span data-stu-id="451f4-117">The serial number.</span></span></param>
        <summary>
            <span data-ttu-id="451f4-118">ゾーン ファイルのシリアル番号を指定します。</span><span class="sxs-lookup"><span data-stu-id="451f4-118">Specifies the serial number for the zone file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="451f4-119">レコードの次のステージでは、更新プログラムを設定します。</span><span class="sxs-lookup"><span data-stu-id="451f4-119">The next stage of the record set update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>