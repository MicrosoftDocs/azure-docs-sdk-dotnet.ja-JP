<Type Name="VirtualMachineCaptureParameters" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters">
  <TypeSignature Language="C#" Value="public class VirtualMachineCaptureParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineCaptureParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineCaptureParameters" />
  <TypeSignature Language="F#" Value="type VirtualMachineCaptureParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4f552-101">仮想マシンのパラメーターをキャプチャします。</span><span class="sxs-lookup"><span data-stu-id="4f552-101">Capture Virtual Machine parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineCaptureParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4f552-102">VirtualMachineCaptureParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4f552-102">Initializes a new instance of the VirtualMachineCaptureParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineCaptureParameters (string vhdPrefix, string destinationContainerName, bool overwriteVhds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vhdPrefix, string destinationContainerName, bool overwriteVhds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters.#ctor(System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (vhdPrefix As String, destinationContainerName As String, overwriteVhds As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters : string * string * bool -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters (vhdPrefix, destinationContainerName, overwriteVhds)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="vhdPrefix" Type="System.String" />
        <Parameter Name="destinationContainerName" Type="System.String" />
        <Parameter Name="overwriteVhds" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="vhdPrefix"><span data-ttu-id="4f552-103">キャプチャした仮想ハード_ディスクの名前プレフィックスです。</span><span class="sxs-lookup"><span data-stu-id="4f552-103">The captured virtual hard disk's name prefix.</span></span></param>
        <param name="destinationContainerName"><span data-ttu-id="4f552-104">移行先のコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="4f552-104">The destination container name.</span></span></param>
        <param name="overwriteVhds"><span data-ttu-id="4f552-105">移行先仮想ハード ディスクの競合が発生した場合に上書きするかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="4f552-105">Specifies whether to overwrite the destination virtual hard disk, in case of conflict.</span></span></param>
        <summary>
            <span data-ttu-id="4f552-106">VirtualMachineCaptureParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4f552-106">Initializes a new instance of the VirtualMachineCaptureParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationContainerName">
      <MemberSignature Language="C#" Value="public string DestinationContainerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DestinationContainerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters.DestinationContainerName" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationContainerName As String" />
      <MemberSignature Language="F#" Value="member this.DestinationContainerName : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters.DestinationContainerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="destinationContainerName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4f552-107">取得または移行先のコンテナー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="4f552-107">Gets or sets the destination container name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OverwriteVhds">
      <MemberSignature Language="C#" Value="public bool OverwriteVhds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool OverwriteVhds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters.OverwriteVhds" />
      <MemberSignature Language="VB.NET" Value="Public Property OverwriteVhds As Boolean" />
      <MemberSignature Language="F#" Value="member this.OverwriteVhds : bool with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters.OverwriteVhds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="overwriteVhds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4f552-108">取得または設定は、移行先仮想ハード ディスクの競合が発生した場合に上書きするかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="4f552-108">Gets or sets specifies whether to overwrite the destination virtual hard disk, in case of conflict.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineCaptureParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4f552-109">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="4f552-109">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4f552-110">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4f552-110">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VhdPrefix">
      <MemberSignature Language="C#" Value="public string VhdPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VhdPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters.VhdPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property VhdPrefix As String" />
      <MemberSignature Language="F#" Value="member this.VhdPrefix : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters.VhdPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vhdPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4f552-111">取得またはキャプチャした仮想ハード_ディスクの名前プレフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="4f552-111">Gets or sets the captured virtual hard disk's name prefix.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>