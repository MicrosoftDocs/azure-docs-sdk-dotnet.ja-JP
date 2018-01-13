<Type Name="SqlQuerySpec" FullName="Microsoft.Azure.Documents.SqlQuerySpec">
  <TypeSignature Language="C#" Value="public sealed class SqlQuerySpec" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SqlQuerySpec extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.SqlQuerySpec" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SqlQuerySpec" />
  <TypeSignature Language="F#" Value="type SqlQuerySpec = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure Cosmos DB サービス SQL クエリを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlQuerySpec ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlQuerySpec.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" /> Azure Cosmos DB サービスのクラスです。</summary>
        <remarks> 
            既定のコンストラクターは、フィールドを既定値に初期化します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlQuerySpec (string queryText);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string queryText) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlQuerySpec.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (queryText As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.SqlQuerySpec : string -&gt; Microsoft.Azure.Documents.SqlQuerySpec" Usage="new Microsoft.Azure.Documents.SqlQuerySpec queryText" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="queryText" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="queryText">クエリのテキスト。</param>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" /> Azure Cosmos DB サービスのクラスです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlQuerySpec (string queryText, Microsoft.Azure.Documents.SqlParameterCollection parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string queryText, class Microsoft.Azure.Documents.SqlParameterCollection parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlQuerySpec.#ctor(System.String,Microsoft.Azure.Documents.SqlParameterCollection)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (queryText As String, parameters As SqlParameterCollection)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.SqlQuerySpec : string * Microsoft.Azure.Documents.SqlParameterCollection -&gt; Microsoft.Azure.Documents.SqlQuerySpec" Usage="new Microsoft.Azure.Documents.SqlQuerySpec (queryText, parameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="queryText" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Documents.SqlParameterCollection" />
      </Parameters>
      <Docs>
        <param name="queryText">データベース クエリのテキストです。</param>
        <param name="parameters"><see cref="T:Microsoft.Azure.Documents.SqlParameterCollection" />インスタンスで、クエリ パラメーターのコレクションを表します。</param>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" /> Azure Cosmos DB サービスのクラスです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.SqlParameterCollection Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.SqlParameterCollection Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.SqlQuerySpec.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As SqlParameterCollection" />
      <MemberSignature Language="F#" Value="member this.Parameters : Microsoft.Azure.Documents.SqlParameterCollection with get, set" Usage="Microsoft.Azure.Documents.SqlQuerySpec.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Name="parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.SqlParameterCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、<see cref="T:Microsoft.Azure.Documents.SqlParameterCollection" />インスタンスで、Azure Cosmos DB クエリ パラメーターのコレクションを表します。
            </summary>
        <value><see cref="T:Microsoft.Azure.Documents.SqlParameterCollection" /> インスタンス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryText">
      <MemberSignature Language="C#" Value="public string QueryText { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QueryText" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.SqlQuerySpec.QueryText" />
      <MemberSignature Language="VB.NET" Value="Public Property QueryText As String" />
      <MemberSignature Language="F#" Value="member this.QueryText : string with get, set" Usage="Microsoft.Azure.Documents.SqlQuerySpec.QueryText" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Name="query")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB データベース クエリのテキストを設定します。
            </summary>
        <value>データベース クエリのテキストです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldSerializeParameters">
      <MemberSignature Language="C#" Value="public bool ShouldSerializeParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool ShouldSerializeParameters() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlQuerySpec.ShouldSerializeParameters" />
      <MemberSignature Language="VB.NET" Value="Public Function ShouldSerializeParameters () As Boolean" />
      <MemberSignature Language="F#" Value="member this.ShouldSerializeParameters : unit -&gt; bool" Usage="sqlQuerySpec.ShouldSerializeParameters " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            示す値を返すかどうか、Azure Cosmos DB データベース<see cref="P:Microsoft.Azure.Documents.SqlQuerySpec.Parameters" />プロパティをシリアル化する必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>