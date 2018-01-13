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
            HttpClient を使用してメタデータ情報を取得します。
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
            <see cref="T:Microsoft.IdentityModel.Protocols.HttpDocumentRetriever" /> クラスの新しいインスタンスを初期化します。
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
            新しいインスタンスを初期化、<see cref="T:Microsoft.IdentityModel.Protocols.HttpDocumentRetriever" />指定 httpClient を持つクラス。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">'httpClient' が null です。</exception>
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
        <param name="address">ドキュメントの場所</param>
        <param name="cancel">キャンセル通知を受け取るために他のオブジェクトまたはスレッドで使用できるキャンセル トークン。 <see cref="T:System.Threading.CancellationToken" /></param>
        <summary>
            タスクを完了すると、指定されたアドレスを使用してリモートのドキュメントから変換された文字列を含むを返します。
            </summary>
        <returns>文字列としてドキュメントします。</returns>
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
            要求の送信にセキュリティで保護されたチャネルの Https が必要です. これは既定でオンにセキュリティ上の理由。 お勧め http アドレスからの取得を許可しない既定でします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>