<Type Name="AdminKeyResult" FullName="Microsoft.Azure.Management.Search.Models.AdminKeyResult">
  <TypeSignature Language="C#" Value="public class AdminKeyResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdminKeyResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.Models.AdminKeyResult" />
  <TypeSignature Language="VB.NET" Value="Public Class AdminKeyResult" />
  <TypeSignature Language="F#" Value="type AdminKeyResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            プライマリおよびセカンダリ管理 API を含む応答は、特定の Azure Search サービスのキーします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdminKeyResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.AdminKeyResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AdminKeyResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdminKeyResult (string primaryKey = null, string secondaryKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string primaryKey, string secondaryKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.AdminKeyResult.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional primaryKey As String = null, Optional secondaryKey As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Search.Models.AdminKeyResult : string * string -&gt; Microsoft.Azure.Management.Search.Models.AdminKeyResult" Usage="new Microsoft.Azure.Management.Search.Models.AdminKeyResult (primaryKey, secondaryKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="primaryKey" Type="System.String" />
        <Parameter Name="secondaryKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="primaryKey">検索サービスのプライマリ管理者 API キー。</param>
        <param name="secondaryKey">検索サービスのセカンダリ管理者 API キー。</param>
        <summary>
            AdminKeyResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryKey">
      <MemberSignature Language="C#" Value="public string PrimaryKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.AdminKeyResult.PrimaryKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryKey As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryKey : string" Usage="Microsoft.Azure.Management.Search.Models.AdminKeyResult.PrimaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primaryKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            検索サービスのプライマリ管理者 API キーを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryKey">
      <MemberSignature Language="C#" Value="public string SecondaryKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.AdminKeyResult.SecondaryKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryKey As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryKey : string" Usage="Microsoft.Azure.Management.Search.Models.AdminKeyResult.SecondaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondaryKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            検索サービスのセカンダリ管理者 API キーを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>