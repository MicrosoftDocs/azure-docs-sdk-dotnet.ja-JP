<Type Name="VirtualMachineStatusCodeCount" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineStatusCodeCount">
  <TypeSignature Language="C#" Value="public class VirtualMachineStatusCodeCount" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineStatusCodeCount extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineStatusCodeCount" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineStatusCodeCount" />
  <TypeSignature Language="F#" Value="type VirtualMachineStatusCodeCount = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3021d-101">ステータス コードと仮想マシンのスケールの数はインスタンスの状態の表示を概要の設定にします。</span><span class="sxs-lookup"><span data-stu-id="3021d-101">The status code and count of the virtual machine scale set instance view status summary.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineStatusCodeCount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineStatusCodeCount.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3021d-102">VirtualMachineStatusCodeCount クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3021d-102">Initializes a new instance of the VirtualMachineStatusCodeCount class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineStatusCodeCount (string code = null, Nullable&lt;int&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, valuetype System.Nullable`1&lt;int32&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineStatusCodeCount.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional count As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineStatusCodeCount : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineStatusCodeCount" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineStatusCodeCount (code, count)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="3021d-103">インスタンス ビューのステータス コード。</span><span class="sxs-lookup"><span data-stu-id="3021d-103">The instance view status code.</span></span></param>
        <param name="count"><span data-ttu-id="3021d-104">特定のステータス コードが、インスタンスの数。</span><span class="sxs-lookup"><span data-stu-id="3021d-104">The number of instances having a particular status code.</span></span></param>
        <summary>
            <span data-ttu-id="3021d-105">VirtualMachineStatusCodeCount クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3021d-105">Initializes a new instance of the VirtualMachineStatusCodeCount class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineStatusCodeCount.Code" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineStatusCodeCount.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3021d-106">インスタンス ビューのステータス コードを取得します。</span><span class="sxs-lookup"><span data-stu-id="3021d-106">Gets the instance view status code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineStatusCodeCount.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineStatusCodeCount.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="count")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3021d-107">特定のステータス コードが、インスタンスの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="3021d-107">Gets the number of instances having a particular status code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>