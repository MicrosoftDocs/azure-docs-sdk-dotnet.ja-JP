<Type Name="DeviceCodeResult" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult">
  <TypeSignature Language="C#" Value="public sealed class DeviceCodeResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeviceCodeResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeviceCodeResult" />
  <TypeSignature Language="F#" Value="type DeviceCodeResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d1526-101">このクラスは、デバイスのコードを要求するときに、サービスからの応答を表します。</span><span class="sxs-lookup"><span data-stu-id="d1526-101">This class represents the response from the service when requesting device code.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult.ClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1526-102">デバイスのコードを要求するクライアントの識別子。</span><span class="sxs-lookup"><span data-stu-id="d1526-102">Identifier of the client requesting device code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceCode">
      <MemberSignature Language="C#" Value="public string DeviceCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult.DeviceCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeviceCode As String" />
      <MemberSignature Language="F#" Value="member this.DeviceCode : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult.DeviceCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1526-103">サービスによって返されたデバイス コード</span><span class="sxs-lookup"><span data-stu-id="d1526-103">Device code returned by the service</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiresOn">
      <MemberSignature Language="C#" Value="public DateTimeOffset ExpiresOn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset ExpiresOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult.ExpiresOn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiresOn As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.ExpiresOn : DateTimeOffset" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult.ExpiresOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1526-104">デバイスのコードの期限が切れる時刻。</span><span class="sxs-lookup"><span data-stu-id="d1526-104">Time when the device code will expire.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Interval">
      <MemberSignature Language="C#" Value="public long Interval { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Interval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult.Interval" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Interval As Long" />
      <MemberSignature Language="F#" Value="member this.Interval : int64" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult.Interval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1526-105">認証フローの完了を確認する間隔の時間をポーリングしています。</span><span class="sxs-lookup"><span data-stu-id="d1526-105">Polling interval time to check for completion of authentication flow.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1526-106">表示目的で使用できるユーザー フレンドリのテキスト応答です。</span><span class="sxs-lookup"><span data-stu-id="d1526-106">User friendly text response that can be used for display purpose.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resource">
      <MemberSignature Language="C#" Value="public string Resource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Resource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult.Resource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Resource As String" />
      <MemberSignature Language="F#" Value="member this.Resource : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult.Resource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1526-107">トークンの受信者となるターゲット リソースの識別子です。</span><span class="sxs-lookup"><span data-stu-id="d1526-107">Identifier of the target resource that would be the recipient of the token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserCode">
      <MemberSignature Language="C#" Value="public string UserCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult.UserCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserCode As String" />
      <MemberSignature Language="F#" Value="member this.UserCode : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult.UserCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1526-108">サービスによって返されるユーザー コード</span><span class="sxs-lookup"><span data-stu-id="d1526-108">User code returned by the service</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerificationUrl">
      <MemberSignature Language="C#" Value="public string VerificationUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VerificationUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult.VerificationUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VerificationUrl As String" />
      <MemberSignature Language="F#" Value="member this.VerificationUrl : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult.VerificationUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1526-109">検証 URL がここで、ユーザーがデバイス コードと資格情報を使用して認証を移動する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d1526-109">Verification URL where the user must navigate to authenticate using the device code and credentials.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>