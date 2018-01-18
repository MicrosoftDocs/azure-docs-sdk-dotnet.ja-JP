<Type Name="SharedKeyLiteCanonicalizer" FullName="Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteCanonicalizer">
  <TypeSignature Language="C#" Value="public sealed class SharedKeyLiteCanonicalizer : Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedKeyLiteCanonicalizer extends System.Object implements class Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteCanonicalizer" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedKeyLiteCanonicalizer&#xA;Implements ICanonicalizer" />
  <TypeSignature Language="F#" Value="type SharedKeyLiteCanonicalizer = class&#xA;    interface ICanonicalizer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="932a8-101">Blob またはキュー サービスの共有キー Lite 認証スキームで署名するための適切な標準形式に HTTP 要求データを変換するカノニカライザーを表します。</span><span class="sxs-lookup"><span data-stu-id="932a8-101">Represents a canonicalizer that converts HTTP request data into a standard form appropriate for signing via the Shared Key Lite authentication scheme for the Blob or Queue service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AuthorizationScheme">
      <MemberSignature Language="C#" Value="public string AuthorizationScheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorizationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteCanonicalizer.AuthorizationScheme" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuthorizationScheme As String" />
      <MemberSignature Language="F#" Value="member this.AuthorizationScheme : string" Usage="Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteCanonicalizer.AuthorizationScheme" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer.AuthorizationScheme</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="932a8-102">正規化に使用する認証スキームを取得します。</span><span class="sxs-lookup"><span data-stu-id="932a8-102">Gets the authorization scheme used for canonicalization.</span></span>
            </summary>
        <value><span data-ttu-id="932a8-103">正規化に使用する認証スキームです。</span><span class="sxs-lookup"><span data-stu-id="932a8-103">The authorization scheme used for canonicalization.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanonicalizeHttpRequest">
      <MemberSignature Language="C#" Value="public string CanonicalizeHttpRequest (System.Net.HttpWebRequest request, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string CanonicalizeHttpRequest(class System.Net.HttpWebRequest request, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteCanonicalizer.CanonicalizeHttpRequest(System.Net.HttpWebRequest,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CanonicalizeHttpRequest (request As HttpWebRequest, accountName As String) As String" />
      <MemberSignature Language="F#" Value="abstract member CanonicalizeHttpRequest : System.Net.HttpWebRequest * string -&gt; string&#xA;override this.CanonicalizeHttpRequest : System.Net.HttpWebRequest * string -&gt; string" Usage="sharedKeyLiteCanonicalizer.CanonicalizeHttpRequest (request, accountName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer.CanonicalizeHttpRequest(System.Net.HttpWebRequest,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.HttpWebRequest" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="932a8-104">HTTP 要求に署名する必要があります。</span><span class="sxs-lookup"><span data-stu-id="932a8-104">The HTTP request that needs to be signed.</span></span></param>
        <param name="accountName"><span data-ttu-id="932a8-105">HTTP 要求にアクセスするストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="932a8-105">The name of the storage account that the HTTP request will access.</span></span></param>
        <summary>
            <span data-ttu-id="932a8-106">指定された HTTP 要求データを署名するための適切な標準形式に変換します。</span><span class="sxs-lookup"><span data-stu-id="932a8-106">Converts the specified HTTP request data into a standard form appropriate for signing.</span></span>
            </summary>
        <returns><span data-ttu-id="932a8-107">署名するための適切な標準形式の HTTP 要求データを含む正規化文字列です。</span><span class="sxs-lookup"><span data-stu-id="932a8-107">The canonicalized string containing the HTTP request data in a standard form appropriate for signing.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Instance">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteCanonicalizer Instance { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteCanonicalizer Instance" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteCanonicalizer.Instance" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Instance As SharedKeyLiteCanonicalizer" />
      <MemberSignature Language="F#" Value="member this.Instance : Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteCanonicalizer" Usage="Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteCanonicalizer.Instance" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteCanonicalizer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="932a8-108">静的インスタンスを取得、<see cref="T:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteCanonicalizer" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="932a8-108">Gets a static instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteCanonicalizer" /> object.</span></span>
            </summary>
        <value><span data-ttu-id="932a8-109">クラスの静的なインスタンス。</span><span class="sxs-lookup"><span data-stu-id="932a8-109">The static instance of the class.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>