<Type Name="HttpBearerChallenge" FullName="Microsoft.Azure.KeyVault.HttpBearerChallenge">
  <TypeSignature Language="C#" Value="public sealed class HttpBearerChallenge" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HttpBearerChallenge extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.HttpBearerChallenge" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HttpBearerChallenge" />
  <TypeSignature Language="F#" Value="type HttpBearerChallenge = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4f6f7-101">Http ベアラー チャレンジ操作を処理します。</span><span class="sxs-lookup"><span data-stu-id="4f6f7-101">Handles http bearer challenge operations</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpBearerChallenge (Uri requestUri, string challenge);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri requestUri, string challenge) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.HttpBearerChallenge.#ctor(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (requestUri As Uri, challenge As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.HttpBearerChallenge : Uri * string -&gt; Microsoft.Azure.KeyVault.HttpBearerChallenge" Usage="new Microsoft.Azure.KeyVault.HttpBearerChallenge (requestUri, challenge)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="requestUri" Type="System.Uri" />
        <Parameter Name="challenge" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="requestUri">To be added.</param>
        <param name="challenge"><span data-ttu-id="4f6f7-102">解析する AuthenticationHeaderValue</span><span class="sxs-lookup"><span data-stu-id="4f6f7-102">The AuthenticationHeaderValue to parse</span></span></param>
        <summary>
            <span data-ttu-id="4f6f7-103">サーバーからの HTTP WWW 認証ベアラー チャレンジを解析します。</span><span class="sxs-lookup"><span data-stu-id="4f6f7-103">Parses an HTTP WWW-Authentication Bearer challenge from a server.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizationServer">
      <MemberSignature Language="C#" Value="public string AuthorizationServer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorizationServer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.HttpBearerChallenge.AuthorizationServer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuthorizationServer As String" />
      <MemberSignature Language="F#" Value="member this.AuthorizationServer : string" Usage="Microsoft.Azure.KeyVault.HttpBearerChallenge.AuthorizationServer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4f6f7-104">存在する場合、承認サーバーの URI にそれを文字列で返します。空</span><span class="sxs-lookup"><span data-stu-id="4f6f7-104">Returns the URI for the Authorization server if present, otherwise string.Empty</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBearerChallenge">
      <MemberSignature Language="C#" Value="public static bool IsBearerChallenge (string challenge);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsBearerChallenge(string challenge) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.HttpBearerChallenge.IsBearerChallenge(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsBearerChallenge (challenge As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsBearerChallenge : string -&gt; bool" Usage="Microsoft.Azure.KeyVault.HttpBearerChallenge.IsBearerChallenge challenge" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="challenge" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="challenge"><span data-ttu-id="4f6f7-105">テストする AuthenticationHeaderValue</span><span class="sxs-lookup"><span data-stu-id="4f6f7-105">The AuthenticationHeaderValue to test</span></span></param>
        <summary>
            <span data-ttu-id="4f6f7-106">認証ヘッダーがベアラー チャレンジであるかどうかをテストします。</span><span class="sxs-lookup"><span data-stu-id="4f6f7-106">Tests whether an authentication header is a Bearer challenge</span></span>
            </summary>
        <returns><span data-ttu-id="4f6f7-107">ヘッダーがベアラー チャレンジの場合は true。</span><span class="sxs-lookup"><span data-stu-id="4f6f7-107">True if the header is a Bearer challenge</span></span></returns>
        <remarks>
            <span data-ttu-id="4f6f7-108">このメソッドは柔軟: かどうかは、パラメーターが null の場合、またはヘッダーのスキームが存在しない場合、これは単に false を返します。</span><span class="sxs-lookup"><span data-stu-id="4f6f7-108">This method is forgiving: if the parameter is null, or the scheme in the header is missing, then it will simply return false.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Resource">
      <MemberSignature Language="C#" Value="public string Resource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Resource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.HttpBearerChallenge.Resource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Resource As String" />
      <MemberSignature Language="F#" Value="member this.Resource : string" Usage="Microsoft.Azure.KeyVault.HttpBearerChallenge.Resource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4f6f7-109">領域の場合は値を返します。 存在する、それ以外の場合、要求、ctor で指定された URI の権限</span><span class="sxs-lookup"><span data-stu-id="4f6f7-109">Returns the Realm value if present, otherwise the Authority of the request URI given in the ctor</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public string Scope { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.HttpBearerChallenge.Scope" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Scope As String" />
      <MemberSignature Language="F#" Value="member this.Scope : string" Usage="Microsoft.Azure.KeyVault.HttpBearerChallenge.Scope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4f6f7-110">スコープ値が存在する場合、それ以外の場合の文字列を返します。空</span><span class="sxs-lookup"><span data-stu-id="4f6f7-110">Returns the Scope value if present, otherwise string.Empty</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceAuthority">
      <MemberSignature Language="C#" Value="public string SourceAuthority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceAuthority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.HttpBearerChallenge.SourceAuthority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceAuthority As String" />
      <MemberSignature Language="F#" Value="member this.SourceAuthority : string" Usage="Microsoft.Azure.KeyVault.HttpBearerChallenge.SourceAuthority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4f6f7-111">要求 URI の権限</span><span class="sxs-lookup"><span data-stu-id="4f6f7-111">The Authority of the request URI</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceUri">
      <MemberSignature Language="C#" Value="public Uri SourceUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri SourceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.HttpBearerChallenge.SourceUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceUri As Uri" />
      <MemberSignature Language="F#" Value="member this.SourceUri : Uri" Usage="Microsoft.Azure.KeyVault.HttpBearerChallenge.SourceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4f6f7-112">ソース URI</span><span class="sxs-lookup"><span data-stu-id="4f6f7-112">The source URI</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetValue">
      <MemberSignature Language="C#" Value="public bool TryGetValue (string key, out string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetValue(string key, [out] string&amp; value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.HttpBearerChallenge.TryGetValue(System.String,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetValue (key As String, ByRef value As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetValue : string *  -&gt; bool" Usage="httpBearerChallenge.TryGetValue (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="4f6f7-113">キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="4f6f7-113">The key to be retrieved</span></span></param>
        <param name="value"><span data-ttu-id="4f6f7-114">指定されたキーの値</span><span class="sxs-lookup"><span data-stu-id="4f6f7-114">The value for the specified key</span></span></param>
        <summary>
            <span data-ttu-id="4f6f7-115">指定したキーに格納された値を返します。</span><span class="sxs-lookup"><span data-stu-id="4f6f7-115">Returns the value stored at the specified key.</span></span>
            </summary>
        <returns><span data-ttu-id="4f6f7-116">できない場合に、キーが見つかった場合は false の場合は true</span><span class="sxs-lookup"><span data-stu-id="4f6f7-116">True when the key is found, false when it is not</span></span></returns>
        <remarks>
            <span data-ttu-id="4f6f7-117">キーが存在しない場合は false を返し、値の内容は変更されません。</span><span class="sxs-lookup"><span data-stu-id="4f6f7-117">If the key does not exist, will return false and the content of value will not be changed</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>