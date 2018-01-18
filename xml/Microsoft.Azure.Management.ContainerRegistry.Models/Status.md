<Type Name="Status" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.Status">
  <TypeSignature Language="C#" Value="public class Status" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Status extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.Status" />
  <TypeSignature Language="VB.NET" Value="Public Class Status" />
  <TypeSignature Language="F#" Value="type Status = class" />
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
            <span data-ttu-id="6e1a5-101">操作が呼び出された時点で Azure のリソースのステータス。</span><span class="sxs-lookup"><span data-stu-id="6e1a5-101">The status of an Azure resource at the time the operation was called.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Status ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Status.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6e1a5-102">ステータス クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6e1a5-102">Initializes a new instance of the Status class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Status (string displayStatus = null, string message = null, Nullable&lt;DateTime&gt; timestamp = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string displayStatus, string message, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; timestamp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Status.#ctor(System.String,System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional displayStatus As String = null, Optional message As String = null, Optional timestamp As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.Status : string * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Status" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.Status (displayStatus, message, timestamp)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="displayStatus" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="timestamp" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="displayStatus"><span data-ttu-id="6e1a5-103">状態の短いラベルです。</span><span class="sxs-lookup"><span data-stu-id="6e1a5-103">The short label for the status.</span></span></param>
        <param name="message"><span data-ttu-id="6e1a5-104">状態は、警告やエラー メッセージなど詳細メッセージ。</span><span class="sxs-lookup"><span data-stu-id="6e1a5-104">The detailed message for the status, including alerts and error messages.</span></span></param>
        <param name="timestamp"><span data-ttu-id="6e1a5-105">現在の値に、状態が変更されたときのタイムスタンプ。</span><span class="sxs-lookup"><span data-stu-id="6e1a5-105">The timestamp when the status was changed to the current value.</span></span></param>
        <summary>
            <span data-ttu-id="6e1a5-106">ステータス クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6e1a5-106">Initializes a new instance of the Status class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayStatus">
      <MemberSignature Language="C#" Value="public string DisplayStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Status.DisplayStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisplayStatus As String" />
      <MemberSignature Language="F#" Value="member this.DisplayStatus : string" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Status.DisplayStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e1a5-107">状態の短いラベルを取得します。</span><span class="sxs-lookup"><span data-stu-id="6e1a5-107">Gets the short label for the status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Status.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Status.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e1a5-108">警告やエラー メッセージなど、状態の詳細なメッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="6e1a5-108">Gets the detailed message for the status, including alerts and error messages.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Timestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Status.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Timestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Timestamp : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Status.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e1a5-109">現在の値に、状態が変更されたときに、タイムスタンプを取得します。</span><span class="sxs-lookup"><span data-stu-id="6e1a5-109">Gets the timestamp when the status was changed to the current value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>