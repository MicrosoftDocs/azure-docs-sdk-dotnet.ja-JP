<Type Name="LocalDataVolume" FullName="Microsoft.Azure.Management.BatchAI.Models.LocalDataVolume">
  <TypeSignature Language="C#" Value="public class LocalDataVolume" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LocalDataVolume extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.LocalDataVolume" />
  <TypeSignature Language="VB.NET" Value="Public Class LocalDataVolume" />
  <TypeSignature Language="F#" Value="type LocalDataVolume = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2fe4b-101">ホスト ディレクトリのコンテナー内のディレクトリへのマッピングを表します。</span><span class="sxs-lookup"><span data-stu-id="2fe4b-101">Represents mapping of host directories to directories in the container.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LocalDataVolume ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.LocalDataVolume.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2fe4b-102">LocalDataVolume クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2fe4b-102">Initializes a new instance of the LocalDataVolume class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LocalDataVolume (string hostPath, string localPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostPath, string localPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.LocalDataVolume.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostPath As String, localPath As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.LocalDataVolume : string * string -&gt; Microsoft.Azure.Management.BatchAI.Models.LocalDataVolume" Usage="new Microsoft.Azure.Management.BatchAI.Models.LocalDataVolume (hostPath, localPath)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostPath" Type="System.String" />
        <Parameter Name="localPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostPath"><span data-ttu-id="2fe4b-103">コンテナー内のディレクトリとしてマウントされるホスト上のパス。</span><span class="sxs-lookup"><span data-stu-id="2fe4b-103">The path on the host that is to be mounted as a directory in the container.</span></span></param>
        <param name="localPath"><span data-ttu-id="2fe4b-104">ホストのディレクトリがマウントされているコンテナー ローカル パスです。</span><span class="sxs-lookup"><span data-stu-id="2fe4b-104">The container local path where the host directory is mounted.</span></span></param>
        <summary>
            <span data-ttu-id="2fe4b-105">LocalDataVolume クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2fe4b-105">Initializes a new instance of the LocalDataVolume class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostPath">
      <MemberSignature Language="C#" Value="public string HostPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.LocalDataVolume.HostPath" />
      <MemberSignature Language="VB.NET" Value="Public Property HostPath As String" />
      <MemberSignature Language="F#" Value="member this.HostPath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.LocalDataVolume.HostPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="hostPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2fe4b-106">取得またはコンテナー内のディレクトリとしてマウントされるホスト上のパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="2fe4b-106">Gets or sets the path on the host that is to be mounted as a directory in the container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalPath">
      <MemberSignature Language="C#" Value="public string LocalPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.LocalDataVolume.LocalPath" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalPath As String" />
      <MemberSignature Language="F#" Value="member this.LocalPath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.LocalDataVolume.LocalPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="localPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2fe4b-107">取得または、ホスト ディレクトリがマウントされているコンテナーのローカル パスを設定します。</span><span class="sxs-lookup"><span data-stu-id="2fe4b-107">Gets or sets the container local path where the host directory is mounted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.LocalDataVolume.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="localDataVolume.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2fe4b-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="2fe4b-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2fe4b-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2fe4b-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>