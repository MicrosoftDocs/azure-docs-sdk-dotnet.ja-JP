<Type Name="Operation" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.Operation">
  <TypeSignature Language="C#" Value="public class Operation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Operation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.Operation" />
  <TypeSignature Language="VB.NET" Value="Public Class Operation" />
  <TypeSignature Language="F#" Value="type Operation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c7010-101">Stream Analytics の REST API 操作</span><span class="sxs-lookup"><span data-stu-id="c7010-101">A Stream Analytics REST API operation</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Operation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.Operation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c7010-102">Operation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c7010-102">Initializes a new instance of the Operation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Operation (string name = null, Microsoft.Azure.Management.StreamAnalytics.Models.OperationDisplay display = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.StreamAnalytics.Models.OperationDisplay display) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.Operation.#ctor(System.String,Microsoft.Azure.Management.StreamAnalytics.Models.OperationDisplay)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional display As OperationDisplay = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.Operation : string * Microsoft.Azure.Management.StreamAnalytics.Models.OperationDisplay -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Operation" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.Operation (name, display)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="display" Type="Microsoft.Azure.Management.StreamAnalytics.Models.OperationDisplay" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="c7010-103">この特定のオブジェクトで実行されている操作の名前。</span><span class="sxs-lookup"><span data-stu-id="c7010-103">The name of the operation being performed on this particular object.</span></span></param>
        <param name="display"><span data-ttu-id="c7010-104">この特定の操作のローカライズされた表示情報が含まれています/アクション。</span><span class="sxs-lookup"><span data-stu-id="c7010-104">Contains the localized display information for this particular operation / action.</span></span></param>
        <summary>
            <span data-ttu-id="c7010-105">Operation クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c7010-105">Initializes a new instance of the Operation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Display">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.OperationDisplay Display { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.OperationDisplay Display" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Operation.Display" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Display As OperationDisplay" />
      <MemberSignature Language="F#" Value="member this.Display : Microsoft.Azure.Management.StreamAnalytics.Models.OperationDisplay" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Operation.Display" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="display")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.OperationDisplay</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c7010-106">取得には、この特定の操作のローカライズされた表示情報が含まれています。/アクション。</span><span class="sxs-lookup"><span data-stu-id="c7010-106">Gets contains the localized display information for this particular operation / action.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Operation.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Operation.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
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
            <span data-ttu-id="c7010-107">この特定のオブジェクトで実行されている操作の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="c7010-107">Gets the name of the operation being performed on this particular object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>