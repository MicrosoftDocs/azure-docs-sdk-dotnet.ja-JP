<Type Name="OperationInfo" FullName="Microsoft.Azure.Management.EventGrid.Models.OperationInfo">
  <TypeSignature Language="C#" Value="public class OperationInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.Models.OperationInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationInfo" />
  <TypeSignature Language="F#" Value="type OperationInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            操作に関する情報
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.OperationInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            OperationInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationInfo (string provider = null, string resource = null, string operation = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string provider, string resource, string operation, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.OperationInfo.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional provider As String = null, Optional resource As String = null, Optional operation As String = null, Optional description As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventGrid.Models.OperationInfo : string * string * string * string -&gt; Microsoft.Azure.Management.EventGrid.Models.OperationInfo" Usage="new Microsoft.Azure.Management.EventGrid.Models.OperationInfo (provider, resource, operation, description)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="provider">プロバイダーの名前</param>
        <param name="resource">リソースの種類の名前</param>
        <param name="operation">操作の名前</param>
        <param name="description">操作の説明</param>
        <summary>
            OperationInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.OperationInfo.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.OperationInfo.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定操作の説明
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public string Operation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.OperationInfo.Operation" />
      <MemberSignature Language="VB.NET" Value="Public Property Operation As String" />
      <MemberSignature Language="F#" Value="member this.Operation : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.OperationInfo.Operation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定操作の名前
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public string Provider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.OperationInfo.Provider" />
      <MemberSignature Language="VB.NET" Value="Public Property Provider As String" />
      <MemberSignature Language="F#" Value="member this.Provider : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.OperationInfo.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定プロバイダーの名前
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resource">
      <MemberSignature Language="C#" Value="public string Resource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Resource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.OperationInfo.Resource" />
      <MemberSignature Language="VB.NET" Value="Public Property Resource As String" />
      <MemberSignature Language="F#" Value="member this.Resource : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.OperationInfo.Resource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、リソースの種類の名前
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>