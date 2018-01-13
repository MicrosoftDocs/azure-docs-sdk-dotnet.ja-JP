<Type Name="FileSystemSource" FullName="Microsoft.Azure.Management.DataFactory.Models.FileSystemSource">
  <TypeSignature Language="C#" Value="public class FileSystemSource : Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileSystemSource extends Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.FileSystemSource" />
  <TypeSignature Language="VB.NET" Value="Public Class FileSystemSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type FileSystemSource = class&#xA;    inherit CopySource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.CopySource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            コピー アクティビティ ファイル システム ソース。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileSystemSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.FileSystemSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            FileSystemSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileSystemSource (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object sourceRetryCount = null, object sourceRetryWait = null, object recursive = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object sourceRetryCount, object sourceRetryWait, object recursive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.FileSystemSource.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional sourceRetryCount As Object = null, Optional sourceRetryWait As Object = null, Optional recursive As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.FileSystemSource : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.FileSystemSource" Usage="new Microsoft.Azure.Management.DataFactory.Models.FileSystemSource (additionalProperties, sourceRetryCount, sourceRetryWait, recursive)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="sourceRetryCount" Type="System.Object" />
        <Parameter Name="sourceRetryWait" Type="System.Object" />
        <Parameter Name="recursive" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="sourceRetryCount">ソースの再試行回数です。 型: 整数 (または式に整数の resultType)。</param>
        <param name="sourceRetryWait">ソースの再試行の待機です。 型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</param>
        <param name="recursive">True の場合、フォルダーのパスの下のファイルには、再帰的が読み取られます。 既定値は true です。 型: ブール値 (または式の resultType ブール値)。</param>
        <summary>
            FileSystemSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recursive">
      <MemberSignature Language="C#" Value="public object Recursive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Recursive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FileSystemSource.Recursive" />
      <MemberSignature Language="VB.NET" Value="Public Property Recursive As Object" />
      <MemberSignature Language="F#" Value="member this.Recursive : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.FileSystemSource.Recursive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recursive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定が true の場合、フォルダーのパスの下のファイルには、再帰的が読み取られます。 既定値は true です。 型: ブール値 (または式の resultType ブール値)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>