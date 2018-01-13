<Type Name="AmazonRedshiftSource" FullName="Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource">
  <TypeSignature Language="C#" Value="public class AmazonRedshiftSource : Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AmazonRedshiftSource extends Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource" />
  <TypeSignature Language="VB.NET" Value="Public Class AmazonRedshiftSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type AmazonRedshiftSource = class&#xA;    inherit CopySource" />
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
            Amazon Redshift ソースのコピー活動元。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AmazonRedshiftSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource.#ctor" />
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
            AmazonRedshiftSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AmazonRedshiftSource (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object sourceRetryCount = null, object sourceRetryWait = null, object query = null, Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings redshiftUnloadSettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object sourceRetryCount, object sourceRetryWait, object query, class Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings redshiftUnloadSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings -&gt; Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource" Usage="new Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource (additionalProperties, sourceRetryCount, sourceRetryWait, query, redshiftUnloadSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="sourceRetryCount" Type="System.Object" />
        <Parameter Name="sourceRetryWait" Type="System.Object" />
        <Parameter Name="query" Type="System.Object" />
        <Parameter Name="redshiftUnloadSettings" Type="Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="sourceRetryCount">ソースの再試行回数です。 型: 整数 (または式に整数の resultType)。</param>
        <param name="sourceRetryWait">ソースの再試行の待機です。 型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</param>
        <param name="query">データベースのクエリ。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="redshiftUnloadSettings">Amazon Redshift からコピーするときに、中間の Amazon S3 に必要な Amazon S3 設定をアンロードします。 これにより、Amazon Redshift ソースからデータをまず S3 にアンロードし、する中間 S3 から対象となるシンクにコピーされます。</param>
        <summary>
            AmazonRedshiftSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public object Query { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Query" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource.Query" />
      <MemberSignature Language="VB.NET" Value="Public Property Query As Object" />
      <MemberSignature Language="F#" Value="member this.Query : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource.Query" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="query")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデータベース クエリを設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedshiftUnloadSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings RedshiftUnloadSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings RedshiftUnloadSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource.RedshiftUnloadSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property RedshiftUnloadSettings As RedshiftUnloadSettings" />
      <MemberSignature Language="F#" Value="member this.RedshiftUnloadSettings : Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource.RedshiftUnloadSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="redshiftUnloadSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.RedshiftUnloadSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアンロードで Amazon Redshift からコピーするときに、中間の Amazon S3 に必要な Amazon S3 設定を設定します。 これにより、Amazon Redshift ソースからデータをまず S3 にアンロードし、する中間 S3 から対象となるシンクにコピーされます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonRedshiftSource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="amazonRedshiftSource.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>