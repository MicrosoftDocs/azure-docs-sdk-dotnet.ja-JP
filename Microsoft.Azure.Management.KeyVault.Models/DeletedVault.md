<Type Name="DeletedVault" FullName="Microsoft.Azure.Management.KeyVault.Models.DeletedVault">
  <TypeSignature Language="C#" Value="public class DeletedVault" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeletedVault extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Models.DeletedVault" />
  <TypeSignature Language="VB.NET" Value="Public Class DeletedVault" />
  <TypeSignature Language="F#" Value="type DeletedVault = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            拡張の詳細を削除した資格情報コンテナー情報です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedVault ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.DeletedVault.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DeletedVault クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedVault (string id = null, string name = null, string type = null, Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, class Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.DeletedVault.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional properties As DeletedVaultProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Models.DeletedVault : string * string * string * Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties -&gt; Microsoft.Azure.Management.KeyVault.Models.DeletedVault" Usage="new Microsoft.Azure.Management.KeyVault.Models.DeletedVault (id, name, type, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties" />
      </Parameters>
      <Docs>
        <param name="id">削除された key vault のリソース ID です。</param>
        <param name="name">Key vault の名前。</param>
        <param name="type">Key vault のリソースの種類。</param>
        <param name="properties">資格情報コンテナーのプロパティ</param>
        <summary>
            DeletedVault クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.DeletedVault.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.KeyVault.Models.DeletedVault.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            削除した、key vault のリソース ID を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.DeletedVault.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.KeyVault.Models.DeletedVault.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Key vault の名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.DeletedVault.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As DeletedVaultProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.DeletedVault.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、資格情報コンテナーのプロパティ
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.DeletedVault.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.KeyVault.Models.DeletedVault.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Key vault のリソースの種類を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>