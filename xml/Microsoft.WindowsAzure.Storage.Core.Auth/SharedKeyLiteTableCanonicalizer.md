<Type Name="SharedKeyLiteTableCanonicalizer" FullName="Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer">
  <TypeSignature Language="C#" Value="public sealed class SharedKeyLiteTableCanonicalizer : Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedKeyLiteTableCanonicalizer extends System.Object implements class Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedKeyLiteTableCanonicalizer&#xA;Implements ICanonicalizer" />
  <TypeSignature Language="F#" Value="type SharedKeyLiteTableCanonicalizer = class&#xA;    interface ICanonicalizer" />
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
            <span data-ttu-id="7c555-101">テーブル サービスの共有キー Lite 認証スキームで署名するための適切な標準形式に HTTP 要求データを変換するカノニカライザーを表します。</span><span class="sxs-lookup"><span data-stu-id="7c555-101">Represents a canonicalizer that converts HTTP request data into a standard form appropriate for signing via the Shared Key Lite authentication scheme for the Table service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AuthorizationScheme">
      <MemberSignature Language="C#" Value="public string AuthorizationScheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorizationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer.AuthorizationScheme" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuthorizationScheme As String" />
      <MemberSignature Language="F#" Value="member this.AuthorizationScheme : string" Usage="Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer.AuthorizationScheme" />
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
            <span data-ttu-id="7c555-102">正規化に使用する認証スキームを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c555-102">Gets the authorization scheme used for canonicalization.</span></span>
            </summary>
        <value><span data-ttu-id="7c555-103">正規化に使用する認証スキームです。</span><span class="sxs-lookup"><span data-stu-id="7c555-103">The authorization scheme used for canonicalization.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanonicalizeHttpRequest">
      <MemberSignature Language="C#" Value="public string CanonicalizeHttpRequest (System.Net.HttpWebRequest request, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string CanonicalizeHttpRequest(class System.Net.HttpWebRequest request, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer.CanonicalizeHttpRequest(System.Net.HttpWebRequest,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CanonicalizeHttpRequest (request As HttpWebRequest, accountName As String) As String" />
      <MemberSignature Language="F#" Value="abstract member CanonicalizeHttpRequest : System.Net.HttpWebRequest * string -&gt; string&#xA;override this.CanonicalizeHttpRequest : System.Net.HttpWebRequest * string -&gt; string" Usage="sharedKeyLiteTableCanonicalizer.CanonicalizeHttpRequest (request, accountName)" />
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
        <param name="request"><span data-ttu-id="7c555-104">HTTP 要求に署名する必要があります。</span><span class="sxs-lookup"><span data-stu-id="7c555-104">The HTTP request that needs to be signed.</span></span></param>
        <param name="accountName"><span data-ttu-id="7c555-105">HTTP 要求にアクセスするストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="7c555-105">The name of the storage account that the HTTP request will access.</span></span></param>
        <summary>
            <span data-ttu-id="7c555-106">指定された HTTP 要求データを署名するための適切な標準形式に変換します。</span><span class="sxs-lookup"><span data-stu-id="7c555-106">Converts the specified HTTP request data into a standard form appropriate for signing.</span></span>
            </summary>
        <returns><span data-ttu-id="7c555-107">署名するための適切な標準形式の HTTP 要求データを含む正規化文字列です。</span><span class="sxs-lookup"><span data-stu-id="7c555-107">The canonicalized string containing the HTTP request data in a standard form appropriate for signing.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Instance">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer Instance { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer Instance" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer.Instance" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Instance As SharedKeyLiteTableCanonicalizer" />
      <MemberSignature Language="F#" Value="member this.Instance : Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer" Usage="Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer.Instance" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c555-108">静的インスタンスを取得、<see cref="T:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7c555-108">Gets a static instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyLiteTableCanonicalizer" /> object.</span></span>
            </summary>
        <value><span data-ttu-id="7c555-109">クラスの静的なインスタンス。</span><span class="sxs-lookup"><span data-stu-id="7c555-109">The static instance of the class.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>