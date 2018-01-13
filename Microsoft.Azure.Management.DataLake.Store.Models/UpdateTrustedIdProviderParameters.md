<Type Name="UpdateTrustedIdProviderParameters" FullName="Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters">
  <TypeSignature Language="C#" Value="public class UpdateTrustedIdProviderParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UpdateTrustedIdProviderParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class UpdateTrustedIdProviderParameters" />
  <TypeSignature Language="F#" Value="type UpdateTrustedIdProviderParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Data Lake Store の信頼された Id プロバイダーがパラメーターを更新します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpdateTrustedIdProviderParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            UpdateTrustedIdProviderParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpdateTrustedIdProviderParameters (string idProvider = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string idProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional idProvider As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters : string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters idProvider" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="idProvider" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="idProvider">この信頼された id プロバイダーの URL</param>
        <summary>
            UpdateTrustedIdProviderParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdProvider">
      <MemberSignature Language="C#" Value="public string IdProvider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IdProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters.IdProvider" />
      <MemberSignature Language="VB.NET" Value="Public Property IdProvider As String" />
      <MemberSignature Language="F#" Value="member this.IdProvider : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters.IdProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.idProvider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこの信頼された id プロバイダーの URL を設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>