<Type Name="Action" FullName="Microsoft.Azure.KeyVault.Models.Action">
  <TypeSignature Language="C#" Value="public class Action" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Action extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.Action" />
  <TypeSignature Language="VB.NET" Value="Public Class Action" />
  <TypeSignature Language="F#" Value="type Action = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            実行されるアクション。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Action ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.Action.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            アクション クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Action (Nullable&lt;Microsoft.Azure.KeyVault.Models.ActionType&gt; actionType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.KeyVault.Models.ActionType&gt; actionType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.Action.#ctor(System.Nullable{Microsoft.Azure.KeyVault.Models.ActionType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional actionType As Nullable(Of ActionType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.Action : Nullable&lt;Microsoft.Azure.KeyVault.Models.ActionType&gt; -&gt; Microsoft.Azure.KeyVault.Models.Action" Usage="new Microsoft.Azure.KeyVault.Models.Action actionType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actionType" Type="System.Nullable&lt;Microsoft.Azure.KeyVault.Models.ActionType&gt;" />
      </Parameters>
      <Docs>
        <param name="actionType">アクションの種類。 使用可能な値が含まれます: 'EmailContacts'、'AutoRenew'</param>
        <summary>
            アクション クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.KeyVault.Models.ActionType&gt; ActionType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.KeyVault.Models.ActionType&gt; ActionType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.Action.ActionType" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionType As Nullable(Of ActionType)" />
      <MemberSignature Language="F#" Value="member this.ActionType : Nullable&lt;Microsoft.Azure.KeyVault.Models.ActionType&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.Action.ActionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="action_type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.KeyVault.Models.ActionType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアクションの種類を設定します。 使用可能な値が含まれます: 'EmailContacts'、'AutoRenew'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>