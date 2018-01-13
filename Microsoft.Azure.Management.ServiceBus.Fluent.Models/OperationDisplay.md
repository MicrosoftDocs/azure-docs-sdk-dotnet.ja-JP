<Type Name="OperationDisplay" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Models.OperationDisplay">
  <TypeSignature Language="C#" Value="public class OperationDisplay" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationDisplay extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Models.OperationDisplay" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationDisplay" />
  <TypeSignature Language="F#" Value="type OperationDisplay = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            操作を表すオブジェクト。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationDisplay ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Models.OperationDisplay.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            OperationDisplay クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationDisplay (string provider = null, string resource = null, string operation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string provider, string resource, string operation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Models.OperationDisplay.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional provider As String = null, Optional resource As String = null, Optional operation As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Fluent.Models.OperationDisplay : string * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Models.OperationDisplay" Usage="new Microsoft.Azure.Management.ServiceBus.Fluent.Models.OperationDisplay (provider, resource, operation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="provider">サービス プロバイダー: Microsoft.ServiceBus</param>
        <param name="resource">操作が実行されるリソース: 請求書などです。</param>
        <param name="operation">操作の種類: 読み取り、書き込み、削除などです。</param>
        <summary>
            OperationDisplay クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public string Operation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.OperationDisplay.Operation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operation As String" />
      <MemberSignature Language="F#" Value="member this.Operation : string" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.OperationDisplay.Operation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            操作の種類を取得します。 読み取り、書き込み、削除などです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public string Provider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.OperationDisplay.Provider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Provider As String" />
      <MemberSignature Language="F#" Value="member this.Provider : string" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.OperationDisplay.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            サービス プロバイダーの取得: Microsoft.ServiceBus
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resource">
      <MemberSignature Language="C#" Value="public string Resource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Resource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.OperationDisplay.Resource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Resource As String" />
      <MemberSignature Language="F#" Value="member this.Resource : string" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.OperationDisplay.Resource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            操作が実行されるリソースを取得: 請求書などです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>