<Type Name="FileDocumentRetriever" FullName="Microsoft.IdentityModel.Protocols.FileDocumentRetriever">
  <TypeSignature Language="C#" Value="public class FileDocumentRetriever : Microsoft.IdentityModel.Protocols.IDocumentRetriever" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileDocumentRetriever extends System.Object implements class Microsoft.IdentityModel.Protocols.IDocumentRetriever" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Protocols.FileDocumentRetriever" />
  <TypeSignature Language="VB.NET" Value="Public Class FileDocumentRetriever&#xA;Implements IDocumentRetriever" />
  <TypeSignature Language="F#" Value="type FileDocumentRetriever = class&#xA;    interface IDocumentRetriever" />
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
            ディスクからローカル ファイルを読み取ります。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileDocumentRetriever ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.FileDocumentRetriever.#ctor" />
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
            <see cref="T:Microsoft.IdentityModel.Protocols.FileDocumentRetriever" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetDocumentAsync (string address, System.Threading.CancellationToken cancel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; GetDocumentAsync(string address, valuetype System.Threading.CancellationToken cancel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.FileDocumentRetriever.GetDocumentAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDocumentAsync (address As String, cancel As CancellationToken) As Task(Of String)" />
      <MemberSignature Language="F#" Value="abstract member GetDocumentAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.GetDocumentAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="fileDocumentRetriever.GetDocumentAsync (address, cancel)" />
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
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Protocols.FileDocumentRetriever/&lt;GetDocumentAsync&gt;d__1))</AttributeName>
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
        <param name="address">ファイルの完全修飾パス。</param>
        <param name="cancel">
          <see cref="T:System.Threading.CancellationToken" />使用しません。</param>
        <summary>
            使用してドキュメントを読み取る<see cref="T:System.IO.FileStream" />です。
            </summary>
        <returns>UTF8 ファイル内のバイトをデコードすることです。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">アドレスが null または空白文字の場合は。</exception>
        <exception cref="T:System.IO.IOException">内部 expection で元の例外を含むです。</exception>
      </Docs>
    </Member>
  </Members>
</Type>