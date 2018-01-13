<Type Name="SqlSource" FullName="Microsoft.Azure.Management.DataFactory.Models.SqlSource">
  <TypeSignature Language="C#" Value="public class SqlSource : Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SqlSource extends Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.SqlSource" />
  <TypeSignature Language="VB.NET" Value="Public Class SqlSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type SqlSource = class&#xA;    inherit CopySource" />
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
            コピー アクティビティ SQL ソース。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SqlSource.#ctor" />
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
            SqlSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlSource (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object sourceRetryCount = null, object sourceRetryWait = null, object sqlReaderQuery = null, object sqlReaderStoredProcedureName = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; storedProcedureParameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object sourceRetryCount, object sourceRetryWait, object sqlReaderQuery, object sqlReaderStoredProcedureName, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; storedProcedureParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SqlSource.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional sourceRetryCount As Object = null, Optional sourceRetryWait As Object = null, Optional sqlReaderQuery As Object = null, Optional sqlReaderStoredProcedureName As Object = null, Optional storedProcedureParameters As IDictionary(Of String, StoredProcedureParameter) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.SqlSource : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.SqlSource" Usage="new Microsoft.Azure.Management.DataFactory.Models.SqlSource (additionalProperties, sourceRetryCount, sourceRetryWait, sqlReaderQuery, sqlReaderStoredProcedureName, storedProcedureParameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="sourceRetryCount" Type="System.Object" />
        <Parameter Name="sourceRetryWait" Type="System.Object" />
        <Parameter Name="sqlReaderQuery" Type="System.Object" />
        <Parameter Name="sqlReaderStoredProcedureName" Type="System.Object" />
        <Parameter Name="storedProcedureParameters" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="sourceRetryCount">ソースの再試行回数です。 型: 整数 (または式に整数の resultType)。</param>
        <param name="sourceRetryWait">ソースの再試行の待機です。 型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</param>
        <param name="sqlReaderQuery">リーダーの SQL クエリ。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="sqlReaderStoredProcedureName">SQL データベースのソースのストアド プロシージャの名前。 これは、SqlReaderQuery と同時に使用できません。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="storedProcedureParameters">値および種類のストアド プロシージャのパラメーターを設定します。 例:"{Parameter1: {値:「1」、種類:"int"}}"。</param>
        <summary>
            SqlSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlReaderQuery">
      <MemberSignature Language="C#" Value="public object SqlReaderQuery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SqlReaderQuery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SqlSource.SqlReaderQuery" />
      <MemberSignature Language="VB.NET" Value="Public Property SqlReaderQuery As Object" />
      <MemberSignature Language="F#" Value="member this.SqlReaderQuery : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SqlSource.SqlReaderQuery" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sqlReaderQuery")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリーダーの SQL クエリを設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlReaderStoredProcedureName">
      <MemberSignature Language="C#" Value="public object SqlReaderStoredProcedureName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SqlReaderStoredProcedureName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SqlSource.SqlReaderStoredProcedureName" />
      <MemberSignature Language="VB.NET" Value="Public Property SqlReaderStoredProcedureName As Object" />
      <MemberSignature Language="F#" Value="member this.SqlReaderStoredProcedureName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SqlSource.SqlReaderStoredProcedureName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sqlReaderStoredProcedureName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または SQL データベースのソースのストアド プロシージャの名前を設定します。 これは、SqlReaderQuery と同時に使用できません。
            型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProcedureParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; StoredProcedureParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; StoredProcedureParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SqlSource.StoredProcedureParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property StoredProcedureParameters As IDictionary(Of String, StoredProcedureParameter)" />
      <MemberSignature Language="F#" Value="member this.StoredProcedureParameters : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SqlSource.StoredProcedureParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storedProcedureParameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.StoredProcedureParameter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の値と型をストアド プロシージャのパラメーターを設定します。 例:"{Parameter1: {値:「1」、種類:"int"}}"。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>