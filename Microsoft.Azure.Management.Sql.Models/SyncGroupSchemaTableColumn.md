<Type Name="SyncGroupSchemaTableColumn" FullName="Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn">
  <TypeSignature Language="C#" Value="public class SyncGroupSchemaTableColumn" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SyncGroupSchemaTableColumn extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn" />
  <TypeSignature Language="VB.NET" Value="Public Class SyncGroupSchemaTableColumn" />
  <TypeSignature Language="F#" Value="type SyncGroupSchemaTableColumn = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            同期グループのテーブルの列のプロパティです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncGroupSchemaTableColumn ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SyncGroupSchemaTableColumn クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncGroupSchemaTableColumn (string quotedName = null, string dataSize = null, string dataType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string quotedName, string dataSize, string dataType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional quotedName As String = null, Optional dataSize As String = null, Optional dataType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn : string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn" Usage="new Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn (quotedName, dataSize, dataType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="quotedName" Type="System.String" />
        <Parameter Name="dataSize" Type="System.String" />
        <Parameter Name="dataType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="quotedName">同期グループのテーブル列の名前を引用符で囲みます。</param>
        <param name="dataSize">列のデータのサイズ。</param>
        <param name="dataType">列のデータ型です。</param>
        <summary>
            SyncGroupSchemaTableColumn クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSize">
      <MemberSignature Language="C#" Value="public string DataSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn.DataSize" />
      <MemberSignature Language="VB.NET" Value="Public Property DataSize As String" />
      <MemberSignature Language="F#" Value="member this.DataSize : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn.DataSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または列のデータ サイズを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataType">
      <MemberSignature Language="C#" Value="public string DataType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn.DataType" />
      <MemberSignature Language="VB.NET" Value="Public Property DataType As String" />
      <MemberSignature Language="F#" Value="member this.DataType : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn.DataType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または列のデータ型を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QuotedName">
      <MemberSignature Language="C#" Value="public string QuotedName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QuotedName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn.QuotedName" />
      <MemberSignature Language="VB.NET" Value="Public Property QuotedName As String" />
      <MemberSignature Language="F#" Value="member this.QuotedName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn.QuotedName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="quotedName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または同期グループのテーブル列の引用符で囲まれた名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>