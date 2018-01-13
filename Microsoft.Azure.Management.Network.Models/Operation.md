<Type Name="Operation" FullName="Microsoft.Azure.Management.Network.Models.Operation">
  <TypeSignature Language="C#" Value="public class Operation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Operation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.Operation" />
  <TypeSignature Language="VB.NET" Value="Public Class Operation" />
  <TypeSignature Language="F#" Value="type Operation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            ネットワーク REST API 操作の定義。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Operation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.Operation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Operation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Operation (string name = null, Microsoft.Azure.Management.Network.Models.OperationDisplay display = null, string origin = null, Microsoft.Azure.Management.Network.Models.OperationPropertiesFormatServiceSpecification serviceSpecification = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.Network.Models.OperationDisplay display, string origin, class Microsoft.Azure.Management.Network.Models.OperationPropertiesFormatServiceSpecification serviceSpecification) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.Operation.#ctor(System.String,Microsoft.Azure.Management.Network.Models.OperationDisplay,System.String,Microsoft.Azure.Management.Network.Models.OperationPropertiesFormatServiceSpecification)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional display As OperationDisplay = null, Optional origin As String = null, Optional serviceSpecification As OperationPropertiesFormatServiceSpecification = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.Operation : string * Microsoft.Azure.Management.Network.Models.OperationDisplay * string * Microsoft.Azure.Management.Network.Models.OperationPropertiesFormatServiceSpecification -&gt; Microsoft.Azure.Management.Network.Models.Operation" Usage="new Microsoft.Azure.Management.Network.Models.Operation (name, display, origin, serviceSpecification)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="display" Type="Microsoft.Azure.Management.Network.Models.OperationDisplay" />
        <Parameter Name="origin" Type="System.String" />
        <Parameter Name="serviceSpecification" Type="Microsoft.Azure.Management.Network.Models.OperationPropertiesFormatServiceSpecification" />
      </Parameters>
      <Docs>
        <param name="name">操作名: {プロバイダー}/{リソース}/{操作}</param>
        <param name="display">操作に関連付けられているメタデータを表示します。</param>
        <param name="origin">操作の原点です。</param>
        <param name="serviceSpecification">サービスの仕様です。</param>
        <summary>
            Operation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Display">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.OperationDisplay Display { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.OperationDisplay Display" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Operation.Display" />
      <MemberSignature Language="VB.NET" Value="Public Property Display As OperationDisplay" />
      <MemberSignature Language="F#" Value="member this.Display : Microsoft.Azure.Management.Network.Models.OperationDisplay with get, set" Usage="Microsoft.Azure.Management.Network.Models.Operation.Display" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="display")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.OperationDisplay</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または操作に関連付けられているメタデータの表示を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Operation.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.Operation.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            取得または設定操作名: {プロバイダー}/{リソース}/{操作}
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Origin">
      <MemberSignature Language="C#" Value="public string Origin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Origin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Operation.Origin" />
      <MemberSignature Language="VB.NET" Value="Public Property Origin As String" />
      <MemberSignature Language="F#" Value="member this.Origin : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.Operation.Origin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="origin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または操作の原点を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceSpecification">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.OperationPropertiesFormatServiceSpecification ServiceSpecification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.OperationPropertiesFormatServiceSpecification ServiceSpecification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.Operation.ServiceSpecification" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceSpecification As OperationPropertiesFormatServiceSpecification" />
      <MemberSignature Language="F#" Value="member this.ServiceSpecification : Microsoft.Azure.Management.Network.Models.OperationPropertiesFormatServiceSpecification with get, set" Usage="Microsoft.Azure.Management.Network.Models.Operation.ServiceSpecification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceSpecification")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.OperationPropertiesFormatServiceSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサービスの仕様を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>