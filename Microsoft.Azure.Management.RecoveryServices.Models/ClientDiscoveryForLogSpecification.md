<Type Name="ClientDiscoveryForLogSpecification" FullName="Microsoft.Azure.Management.RecoveryServices.Models.ClientDiscoveryForLogSpecification">
  <TypeSignature Language="C#" Value="public class ClientDiscoveryForLogSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClientDiscoveryForLogSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Models.ClientDiscoveryForLogSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class ClientDiscoveryForLogSpecification" />
  <TypeSignature Language="F#" Value="type ClientDiscoveryForLogSpecification = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            操作のログの仕様です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientDiscoveryForLogSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.ClientDiscoveryForLogSpecification.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ClientDiscoveryForLogSpecification クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientDiscoveryForLogSpecification (string name = null, string displayName = null, Nullable&lt;DateTime&gt; blobDuration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string displayName, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; blobDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.ClientDiscoveryForLogSpecification.#ctor(System.String,System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional displayName As String = null, Optional blobDuration As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Models.ClientDiscoveryForLogSpecification : string * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Models.ClientDiscoveryForLogSpecification" Usage="new Microsoft.Azure.Management.RecoveryServices.Models.ClientDiscoveryForLogSpecification (name, displayName, blobDuration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="blobDuration" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="name">ログの名前です。</param>
        <param name="displayName">ローカライズされた表示名。</param>
        <param name="blobDuration">Blob の期間です。</param>
        <summary>
            ClientDiscoveryForLogSpecification クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; BlobDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; BlobDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ClientDiscoveryForLogSpecification.BlobDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BlobDuration As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.BlobDuration : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ClientDiscoveryForLogSpecification.BlobDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blobDuration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            期間の blob を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ClientDiscoveryForLogSpecification.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ClientDiscoveryForLogSpecification.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得のローカライズされた表示名。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ClientDiscoveryForLogSpecification.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ClientDiscoveryForLogSpecification.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
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
            ログの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>