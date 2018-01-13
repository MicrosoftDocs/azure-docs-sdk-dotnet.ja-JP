<Type Name="ShardedTableInfo" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo">
  <TypeSignature Language="C#" Value="public class ShardedTableInfo : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.TableInfo, IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit ShardedTableInfo extends Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.TableInfo implements class System.IEquatable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class ShardedTableInfo&#xA;Inherits TableInfo&#xA;Implements IEquatable(Of ShardedTableInfo)" />
  <TypeSignature Language="F#" Value="type ShardedTableInfo = class&#xA;    inherit TableInfo&#xA;    interface IEquatable&lt;ShardedTableInfo&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.TableInfo</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="ShardedTableInfo", Namespace="")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            1 つのシャードされたテーブルに関する情報を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ShardedTableInfo (string tableName, string columnName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tableName, string columnName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tableName As String, columnName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo : string * string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo (tableName, columnName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="columnName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableName">シャーディングされたテーブルの名前です。</param>
        <param name="columnName">シャード キー列の名前。</param>
        <summary>
            <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ShardedTableInfo (string schemaName, string tableName, string columnName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string schemaName, string tableName, string columnName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (schemaName As String, tableName As String, columnName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo : string * string * string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo (schemaName, tableName, columnName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="columnName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="schemaName">シャードされたテーブルのスキーマ名。</param>
        <param name="tableName">シャーディングされたテーブルの名前です。</param>
        <param name="columnName">シャード キー列の名前。</param>
        <summary>
            <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo.Equals(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As ShardedTableInfo) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo -&gt; bool" Usage="shardedTableInfo.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo" />
      </Parameters>
      <Docs>
        <param name="other">現在のオブジェクトと比較する ShardedTableInfo オブジェクト。</param>
        <summary>
            指定した ShardedTableInfo オブジェクトが現在のオブジェクトと等しいかどうかを判断します。
            </summary>
        <returns>指定した ShardedTableInfo オブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="shardedTableInfo.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">現在の ShardedTableInfo オブジェクトと比較するオブジェクト。</param>
        <summary>
            オブジェクト クラスの Equals() メソッドをオーバーライドします。 指定したオブジェクトが、現在のオブジェクトと等しいかどうかを判断します。
            </summary>
        <returns>指定したオブジェクトが現在の ShardedTableInfo オブジェクトと等しい場合は true。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="shardedTableInfo.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            このインスタンスのハッシュ コードを計算します。
            </summary>
        <returns>オブジェクトのハッシュ コード。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyColumnName">
      <MemberSignature Language="C#" Value="public string KeyColumnName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyColumnName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo.KeyColumnName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyColumnName As String" />
      <MemberSignature Language="F#" Value="member this.KeyColumnName : string" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo.KeyColumnName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            シャード キー列の名前です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>