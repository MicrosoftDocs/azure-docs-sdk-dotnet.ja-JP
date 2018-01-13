<Type Name="AzureTableSource" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureTableSource">
  <TypeSignature Language="C#" Value="public class AzureTableSource : Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureTableSource extends Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureTableSource" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureTableSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type AzureTableSource = class&#xA;    inherit CopySource" />
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
            コピー アクティビティの Azure テーブル ソースです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureTableSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureTableSource.#ctor" />
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
            AzureTableSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureTableSource (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object sourceRetryCount = null, object sourceRetryWait = null, object azureTableSourceQuery = null, object azureTableSourceIgnoreTableNotFound = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object sourceRetryCount, object sourceRetryWait, object azureTableSourceQuery, object azureTableSourceIgnoreTableNotFound) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureTableSource.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional sourceRetryCount As Object = null, Optional sourceRetryWait As Object = null, Optional azureTableSourceQuery As Object = null, Optional azureTableSourceIgnoreTableNotFound As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureTableSource : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureTableSource" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureTableSource (additionalProperties, sourceRetryCount, sourceRetryWait, azureTableSourceQuery, azureTableSourceIgnoreTableNotFound)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="sourceRetryCount" Type="System.Object" />
        <Parameter Name="sourceRetryWait" Type="System.Object" />
        <Parameter Name="azureTableSourceQuery" Type="System.Object" />
        <Parameter Name="azureTableSourceIgnoreTableNotFound" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="sourceRetryCount">ソースの再試行回数です。 型: 整数 (または式に整数の resultType)。</param>
        <param name="sourceRetryWait">ソースの再試行の待機です。 型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</param>
        <param name="azureTableSourceQuery">Azure のテーブル ソース クエリです。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="azureTableSourceIgnoreTableNotFound">Azure のテーブル ソースは、テーブルが見つかりません。 を無視します。 型: ブール値 (または式の resultType ブール値)。</param>
        <summary>
            AzureTableSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableSourceIgnoreTableNotFound">
      <MemberSignature Language="C#" Value="public object AzureTableSourceIgnoreTableNotFound { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AzureTableSourceIgnoreTableNotFound" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureTableSource.AzureTableSourceIgnoreTableNotFound" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTableSourceIgnoreTableNotFound As Object" />
      <MemberSignature Language="F#" Value="member this.AzureTableSourceIgnoreTableNotFound : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureTableSource.AzureTableSourceIgnoreTableNotFound" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureTableSourceIgnoreTableNotFound")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはソース テーブルが見つかりません。 を無視する azure のテーブルを設定します。 型: ブール値 (または式の resultType ブール値)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableSourceQuery">
      <MemberSignature Language="C#" Value="public object AzureTableSourceQuery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AzureTableSourceQuery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureTableSource.AzureTableSourceQuery" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTableSourceQuery As Object" />
      <MemberSignature Language="F#" Value="member this.AzureTableSourceQuery : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureTableSource.AzureTableSourceQuery" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureTableSourceQuery")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または azure のテーブル ソース クエリを設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>