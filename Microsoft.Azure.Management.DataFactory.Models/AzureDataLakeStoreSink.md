<Type Name="AzureDataLakeStoreSink" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreSink">
  <TypeSignature Language="C#" Value="public class AzureDataLakeStoreSink : Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureDataLakeStoreSink extends Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreSink" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureDataLakeStoreSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type AzureDataLakeStoreSink = class&#xA;    inherit CopySink" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.CopySink</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            コピー アクティビティの Azure Data Lake Store シンクです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureDataLakeStoreSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreSink.#ctor" />
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
            AzureDataLakeStoreSink クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureDataLakeStoreSink (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object writeBatchSize = null, object writeBatchTimeout = null, object sinkRetryCount = null, object sinkRetryWait = null, string copyBehavior = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object writeBatchSize, object writeBatchTimeout, object sinkRetryCount, object sinkRetryWait, string copyBehavior) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreSink.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional writeBatchSize As Object = null, Optional writeBatchTimeout As Object = null, Optional sinkRetryCount As Object = null, Optional sinkRetryWait As Object = null, Optional copyBehavior As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreSink : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * string -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreSink" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreSink (additionalProperties, writeBatchSize, writeBatchTimeout, sinkRetryCount, sinkRetryWait, copyBehavior)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="writeBatchSize" Type="System.Object" />
        <Parameter Name="writeBatchTimeout" Type="System.Object" />
        <Parameter Name="sinkRetryCount" Type="System.Object" />
        <Parameter Name="sinkRetryWait" Type="System.Object" />
        <Parameter Name="copyBehavior" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="writeBatchSize">バッチ サイズを記述します。 型: 整数 (または式と resultType 整数)、最小値: 0。</param>
        <param name="writeBatchTimeout">バッチ タイムアウトを記述します。 型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</param>
        <param name="sinkRetryCount">再試行回数をシンクします。 型: 整数 (または式に整数の resultType)。</param>
        <param name="sinkRetryWait">再試行の待機をシンクします。 型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</param>
        <param name="copyBehavior">コピー シンクのコピー動作の型。
            使用可能な値が含まれます: 'PreserveHierarchy'、'FlattenHierarchy'、'MergeFiles'</param>
        <summary>
            AzureDataLakeStoreSink クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyBehavior">
      <MemberSignature Language="C#" Value="public string CopyBehavior { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CopyBehavior" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreSink.CopyBehavior" />
      <MemberSignature Language="VB.NET" Value="Public Property CopyBehavior As String" />
      <MemberSignature Language="F#" Value="member this.CopyBehavior : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreSink.CopyBehavior" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="copyBehavior")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコピー シンクのコピー動作の種類を設定します。 使用可能な値が含まれます: 'PreserveHierarchy'、'FlattenHierarchy'、'MergeFiles'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>