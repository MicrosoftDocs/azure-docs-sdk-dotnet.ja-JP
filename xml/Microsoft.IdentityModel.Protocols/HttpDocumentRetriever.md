<Type Name="HttpDocumentRetriever" FullName="Microsoft.IdentityModel.Protocols.HttpDocumentRetriever">
  <TypeSignature Language="C#" Value="public class HttpDocumentRetriever : Microsoft.IdentityModel.Protocols.IDocumentRetriever" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HttpDocumentRetriever extends System.Object implements class Microsoft.IdentityModel.Protocols.IDocumentRetriever" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Protocols.HttpDocumentRetriever" />
  <TypeSignature Language="VB.NET" Value="Public Class HttpDocumentRetriever&#xA;Implements IDocumentRetriever" />
  <TypeSignature Language="F#" Value="type HttpDocumentRetriever = class&#xA;    interface IDocumentRetriever" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
    <AssemblyVersion>2.1.3.0</AssemblyVersion>
    <AssemblyVersion>5.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.IdentityModel.Protocols.IDocumentRetriever</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="8dc84-101">HttpClient を使用してメタデータ情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8dc84-101">Retrieves metadata information using HttpClient.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpDocumentRetriever ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.HttpDocumentRetriever.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8dc84-102"><see cref="T:Microsoft.IdentityModel.Protocols.HttpDocumentRetriever" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8dc84-102">Initializes a new instance of the <see cref="T:Microsoft.IdentityModel.Protocols.HttpDocumentRetriever" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpDocumentRetriever (System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.HttpDocumentRetriever.#ctor(System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Protocols.HttpDocumentRetriever : System.Net.Http.HttpClient -&gt; Microsoft.IdentityModel.Protocols.HttpDocumentRetriever" Usage="new Microsoft.IdentityModel.Protocols.HttpDocumentRetriever httpClient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="httpClient">
          <see cref="T:System.Net.Http.HttpClient" />
        </param>
        <summary>
            <span data-ttu-id="8dc84-103">新しいインスタンスを初期化、<see cref="T:Microsoft.IdentityModel.Protocols.HttpDocumentRetriever" />指定 httpClient を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="8dc84-103">Initializes a new instance of the <see cref="T:Microsoft.IdentityModel.Protocols.HttpDocumentRetriever" /> class with a specified httpClient.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="8dc84-104">'httpClient' が null です。</span><span class="sxs-lookup"><span data-stu-id="8dc84-104">'httpClient' is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetDocumentAsync (string address, System.Threading.CancellationToken cancel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; GetDocumentAsync(string address, valuetype System.Threading.CancellationToken cancel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.HttpDocumentRetriever.GetDocumentAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDocumentAsync (address As String, cancel As CancellationToken) As Task(Of String)" />
      <MemberSignature Language="F#" Value="abstract member GetDocumentAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.GetDocumentAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="httpDocumentRetriever.GetDocumentAsync (address, cancel)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.IdentityModel.Protocols.IDocumentRetriever.GetDocumentAsync(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.DebuggerStepThrough</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Protocols.HttpDocumentRetriever/&lt;GetDocumentAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="cancel" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="8dc84-105">ドキュメントの場所</span><span class="sxs-lookup"><span data-stu-id="8dc84-105">Location of document</span></span></param>
        <param name="cancel"><span data-ttu-id="8dc84-106">キャンセル通知を受け取るために他のオブジェクトまたはスレッドで使用できるキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8dc84-106">A cancellation token that can be used by other objects or threads to receive notice of cancellation.</span></span> <see cref="T:System.Threading.CancellationToken" /></param>
        <summary>
            <span data-ttu-id="8dc84-107">タスクを完了すると、指定されたアドレスを使用してリモートのドキュメントから変換された文字列を含むを返します。</span><span class="sxs-lookup"><span data-stu-id="8dc84-107">Returns a task which contains a string converted from remote document when completed, by using the provided address.</span></span>
            </summary>
        <returns><span data-ttu-id="8dc84-108">文字列としてドキュメントします。</span><span class="sxs-lookup"><span data-stu-id="8dc84-108">Document as a string</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequireHttps">
      <MemberSignature Language="C#" Value="public bool RequireHttps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequireHttps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Protocols.HttpDocumentRetriever.RequireHttps" />
      <MemberSignature Language="VB.NET" Value="Public Property RequireHttps As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequireHttps : bool with get, set" Usage="Microsoft.IdentityModel.Protocols.HttpDocumentRetriever.RequireHttps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8dc84-109">要求の送信にセキュリティで保護されたチャネルの Https が必要です.</span><span class="sxs-lookup"><span data-stu-id="8dc84-109">Requires Https secure channel for sending requests..</span></span> <span data-ttu-id="8dc84-110">これは既定でオンにセキュリティ上の理由。</span><span class="sxs-lookup"><span data-stu-id="8dc84-110">This is turned ON by default for security reasons.</span></span> <span data-ttu-id="8dc84-111">お勧め http アドレスからの取得を許可しない既定でします。</span><span class="sxs-lookup"><span data-stu-id="8dc84-111">It is RECOMMENDED that you do not allow retrieval from http addresses by default.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>