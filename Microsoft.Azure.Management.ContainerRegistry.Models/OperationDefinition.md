<Type Name="OperationDefinition" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition">
  <TypeSignature Language="C#" Value="public class OperationDefinition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationDefinition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationDefinition" />
  <TypeSignature Language="F#" Value="type OperationDefinition = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            コンテナーのレジストリ操作の定義。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationDefinition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            OperationDefinition クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationDefinition (string name = null, Microsoft.Azure.Management.ContainerRegistry.Models.OperationDisplayDefinition display = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.ContainerRegistry.Models.OperationDisplayDefinition display) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition.#ctor(System.String,Microsoft.Azure.Management.ContainerRegistry.Models.OperationDisplayDefinition)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional display As OperationDisplayDefinition = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition : string * Microsoft.Azure.Management.ContainerRegistry.Models.OperationDisplayDefinition -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition (name, display)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="display" Type="Microsoft.Azure.Management.ContainerRegistry.Models.OperationDisplayDefinition" />
      </Parameters>
      <Docs>
        <param name="name">操作名: {プロバイダー}/{リソース}/{操作}。</param>
        <param name="display">コンテナーのレジストリ操作の表示情報。</param>
        <summary>
            OperationDefinition クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Display">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.OperationDisplayDefinition Display { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.OperationDisplayDefinition Display" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition.Display" />
      <MemberSignature Language="VB.NET" Value="Public Property Display As OperationDisplayDefinition" />
      <MemberSignature Language="F#" Value="member this.Display : Microsoft.Azure.Management.ContainerRegistry.Models.OperationDisplayDefinition with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition.Display" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="display")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.OperationDisplayDefinition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンテナーのレジストリ操作の表示情報を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
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
            取得または設定操作名: {プロバイダー}/{リソース}/{操作}。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>