<Type Name="FailoverRequest" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest">
  <TypeSignature Language="C#" Value="public class FailoverRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FailoverRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class FailoverRequest" />
  <TypeSignature Language="F#" Value="type FailoverRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="048c2-101">ターゲット デバイスにソース デバイスからのボリューム コンテナーのフェールオーバーをトリガーするための要求オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="048c2-101">The request object for triggering a failover of volume containers, from a source device to a target device.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="048c2-102">FailoverRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="048c2-102">Initializes a new instance of the FailoverRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverRequest (string targetDeviceId = null, System.Collections.Generic.IList&lt;string&gt; volumeContainers = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetDeviceId, class System.Collections.Generic.IList`1&lt;string&gt; volumeContainers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest.#ctor(System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional targetDeviceId As String = null, Optional volumeContainers As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest : string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest (targetDeviceId, volumeContainers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetDeviceId" Type="System.String" />
        <Parameter Name="volumeContainers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="targetDeviceId"><span data-ttu-id="048c2-103">フェールオーバー ターゲットとして機能するデバイスの ARM パス ID。</span><span class="sxs-lookup"><span data-stu-id="048c2-103">The ARM path ID of the device which will act as the failover target.</span></span></param>
        <param name="volumeContainers"><span data-ttu-id="048c2-104">パスでは、フェールオーバーのターゲット デバイスにする必要があるボリューム コンテナーの Id の一覧。</span><span class="sxs-lookup"><span data-stu-id="048c2-104">The list of path IDs of the volume containers which needs to be failed-over to the target device.</span></span></param>
        <summary>
            <span data-ttu-id="048c2-105">FailoverRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="048c2-105">Initializes a new instance of the FailoverRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDeviceId">
      <MemberSignature Language="C#" Value="public string TargetDeviceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetDeviceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest.TargetDeviceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDeviceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetDeviceId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest.TargetDeviceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetDeviceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="048c2-106">取得またはフェールオーバー ターゲットとして機能するデバイスの ARM パス ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="048c2-106">Gets or sets the ARM path ID of the device which will act as the failover target.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeContainers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; VolumeContainers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; VolumeContainers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest.VolumeContainers" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeContainers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.VolumeContainers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest.VolumeContainers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="volumeContainers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="048c2-107">取得またはパスでは、フェールオーバーのターゲット デバイスにする必要があるボリューム コンテナーの Id の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="048c2-107">Gets or sets the list of path IDs of the volume containers which needs to be failed-over to the target device.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>