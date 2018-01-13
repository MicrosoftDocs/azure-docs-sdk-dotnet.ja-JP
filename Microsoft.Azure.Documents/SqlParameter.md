<Type Name="SqlParameter" FullName="Microsoft.Azure.Documents.SqlParameter">
  <TypeSignature Language="C#" Value="public sealed class SqlParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SqlParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.SqlParameter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SqlParameter" />
  <TypeSignature Language="F#" Value="type SqlParameter = class" />
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
            関連付けられているパラメーターを表す<see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />Cosmos DB の Azure サービスにします。
            </summary>
    <remarks>
            Azure Cosmos DB SQL パラメーターは、パラメーター化クエリで参照されている名前と値のペアです。 異なり関係 SQL データベースで必要はありませんそれらに関連付けられている型。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameter.#ctor" />
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
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.SqlParameter" /> Azure Cosmos DB サービスのクラスです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlParameter (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameter.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.SqlParameter : string -&gt; Microsoft.Azure.Documents.SqlParameter" Usage="new Microsoft.Azure.Documents.SqlParameter name" />
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
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">パラメーターの名前。</param>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.SqlParameter" /> Azure Cosmos DB サービスのパラメーターの名前を持つクラス。
            </summary>
        <remarks>パラメーターの名前が始まる必要があります ' @' 有効な SQL 識別子であるとします。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlParameter (string name, object value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, object value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameter.#ctor(System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, value As Object)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.SqlParameter : string * obj -&gt; Microsoft.Azure.Documents.SqlParameter" Usage="new Microsoft.Azure.Documents.SqlParameter (name, value)" />
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
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="name">パラメーターの名前。</param>
        <param name="value">パラメーターの値。</param>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.SqlParameter" /> Azure Cosmos DB サービスのパラメーターの値と名前を持つクラス。
            </summary>
        <remarks>パラメーターの名前が始まる必要があります ' @' 有効な SQL 識別子であるとします。 値は、シリアル化およびとして渡される JSON ドキュメントのクエリを取得します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.SqlParameter.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Documents.SqlParameter.Name" />
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
          <AttributeName>System.Runtime.Serialization.DataMember(Name="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスのパラメーターの名前を設定します。
            </summary>
        <value>パラメーターの名前。</value>
        <remarks>パラメーターの名前が始まる必要があります ' @' 有効な SQL 識別子であるとします。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public object Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.SqlParameter.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As Object" />
      <MemberSignature Language="F#" Value="member this.Value : obj with get, set" Usage="Microsoft.Azure.Documents.SqlParameter.Value" />
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
          <AttributeName>System.Runtime.Serialization.DataMember(Name="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスのパラメーターの値を設定します。
            </summary>
        <value>パラメーターの値。</value>
        <remarks>値は、シリアル化およびとして渡される JSON ドキュメントのクエリを取得します。</remarks>
      </Docs>
    </Member>
  </Members>
</Type>