<Type Name="BlobSource" FullName="Microsoft.Azure.Management.DataFactory.Models.BlobSource">
  <TypeSignature Language="C#" Value="public class BlobSource : Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BlobSource extends Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.BlobSource" />
  <TypeSignature Language="VB.NET" Value="Public Class BlobSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type BlobSource = class&#xA;    inherit CopySource" />
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
            コピー アクティビティの Azure Blob ソース。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.BlobSource.#ctor" />
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
            BlobSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobSource (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object sourceRetryCount = null, object sourceRetryWait = null, object treatEmptyAsNull = null, object skipHeaderLineCount = null, object recursive = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object sourceRetryCount, object sourceRetryWait, object treatEmptyAsNull, object skipHeaderLineCount, object recursive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.BlobSource.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional sourceRetryCount As Object = null, Optional sourceRetryWait As Object = null, Optional treatEmptyAsNull As Object = null, Optional skipHeaderLineCount As Object = null, Optional recursive As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.BlobSource : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.BlobSource" Usage="new Microsoft.Azure.Management.DataFactory.Models.BlobSource (additionalProperties, sourceRetryCount, sourceRetryWait, treatEmptyAsNull, skipHeaderLineCount, recursive)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="sourceRetryCount" Type="System.Object" />
        <Parameter Name="sourceRetryWait" Type="System.Object" />
        <Parameter Name="treatEmptyAsNull" Type="System.Object" />
        <Parameter Name="skipHeaderLineCount" Type="System.Object" />
        <Parameter Name="recursive" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="sourceRetryCount">ソースの再試行回数です。 型: 整数 (または式に整数の resultType)。</param>
        <param name="sourceRetryWait">ソースの再試行の待機です。 型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</param>
        <param name="treatEmptyAsNull">Null と空に処理します。 型: ブール値 (または式の resultType ブール値)。</param>
        <param name="skipHeaderLineCount">各 blob からスキップするヘッダー行の数。 型: 整数 (または式に整数の resultType)。</param>
        <param name="recursive">True の場合、フォルダーのパスの下のファイルには、再帰的が読み取られます。 既定値は true です。 型: ブール値 (または式の resultType ブール値)。</param>
        <summary>
            BlobSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recursive">
      <MemberSignature Language="C#" Value="public object Recursive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Recursive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.BlobSource.Recursive" />
      <MemberSignature Language="VB.NET" Value="Public Property Recursive As Object" />
      <MemberSignature Language="F#" Value="member this.Recursive : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.BlobSource.Recursive" />
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
    <Member MemberName="SkipHeaderLineCount">
      <MemberSignature Language="C#" Value="public object SkipHeaderLineCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SkipHeaderLineCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.BlobSource.SkipHeaderLineCount" />
      <MemberSignature Language="VB.NET" Value="Public Property SkipHeaderLineCount As Object" />
      <MemberSignature Language="F#" Value="member this.SkipHeaderLineCount : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.BlobSource.SkipHeaderLineCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="skipHeaderLineCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または各 blob からスキップするヘッダー行の数を設定します。 型: 整数 (または式に整数の resultType)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TreatEmptyAsNull">
      <MemberSignature Language="C#" Value="public object TreatEmptyAsNull { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TreatEmptyAsNull" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.BlobSource.TreatEmptyAsNull" />
      <MemberSignature Language="VB.NET" Value="Public Property TreatEmptyAsNull As Object" />
      <MemberSignature Language="F#" Value="member this.TreatEmptyAsNull : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.BlobSource.TreatEmptyAsNull" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="treatEmptyAsNull")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、null と空扱います。 型: ブール値 (または式の resultType ブール値)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>