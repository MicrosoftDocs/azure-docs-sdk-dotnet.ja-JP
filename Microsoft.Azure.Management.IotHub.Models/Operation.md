<Type Name="Operation" FullName="Microsoft.Azure.Management.IotHub.Models.Operation">
  <TypeSignature Language="C#" Value="public class Operation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Operation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.Operation" />
  <TypeSignature Language="VB.NET" Value="Public Class Operation" />
  <TypeSignature Language="F#" Value="type Operation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            IoT Hub の REST API の操作
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Operation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.Operation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Operation (string name = null, Microsoft.Azure.Management.IotHub.Models.OperationDisplay display = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.IotHub.Models.OperationDisplay display) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.Operation.#ctor(System.String,Microsoft.Azure.Management.IotHub.Models.OperationDisplay)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional display As OperationDisplay = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.Operation : string * Microsoft.Azure.Management.IotHub.Models.OperationDisplay -&gt; Microsoft.Azure.Management.IotHub.Models.Operation" Usage="new Microsoft.Azure.Management.IotHub.Models.Operation (name, display)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="display" Type="Microsoft.Azure.Management.IotHub.Models.OperationDisplay" />
      </Parameters>
      <Docs>
        <param name="name">操作名: {プロバイダー}/{リソース}/{読み取り | 書き込み | アクション | 削除}</param>
        <param name="display">操作を表すオブジェクト。</param>
        <summary>
            Operation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Display">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.IotHub.Models.OperationDisplay Display { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.IotHub.Models.OperationDisplay Display" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.Operation.Display" />
      <MemberSignature Language="VB.NET" Value="Public Property Display As OperationDisplay" />
      <MemberSignature Language="F#" Value="member this.Display : Microsoft.Azure.Management.IotHub.Models.OperationDisplay with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.Operation.Display" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="display")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.OperationDisplay</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の操作を表すオブジェクト。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.Operation.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.IotHub.Models.Operation.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            操作の名前を取得: {プロバイダー}/{リソース}/{読み取り | 書き込み | アクション | を削除}
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>