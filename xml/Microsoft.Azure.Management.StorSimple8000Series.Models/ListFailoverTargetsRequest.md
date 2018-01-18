<Type Name="ListFailoverTargetsRequest" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest">
  <TypeSignature Language="C#" Value="public class ListFailoverTargetsRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ListFailoverTargetsRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class ListFailoverTargetsRequest" />
  <TypeSignature Language="F#" Value="type ListFailoverTargetsRequest = class" />
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
            <span data-ttu-id="1d6af-101">フェールオーバーのターゲット (フェールオーバーの対象となるデバイス) の一覧をフェッチするための要求オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="1d6af-101">The request object for fetching the list of failover targets (eligible devices for failover).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ListFailoverTargetsRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1d6af-102">ListFailoverTargetsRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1d6af-102">Initializes a new instance of the ListFailoverTargetsRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ListFailoverTargetsRequest (System.Collections.Generic.IList&lt;string&gt; volumeContainers = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; volumeContainers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest.#ctor(System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional volumeContainers As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest : System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest volumeContainers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="volumeContainers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="volumeContainers"><span data-ttu-id="1d6af-103">パスの一覧を選びましたフェイル オーバーする必要があるボリューム コンテナーの Id は、対象の式を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d6af-103">The list of path IDs of the volume containers that needs to be failed-over, for which we want to fetch the eligible targets.</span></span></param>
        <summary>
            <span data-ttu-id="1d6af-104">ListFailoverTargetsRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1d6af-104">Initializes a new instance of the ListFailoverTargetsRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeContainers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; VolumeContainers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; VolumeContainers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest.VolumeContainers" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeContainers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.VolumeContainers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest.VolumeContainers" />
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
            <span data-ttu-id="1d6af-105">取得またはパスの対象の式を取得する対象のフェイル オーバーする必要があるボリューム コンテナーの Id の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="1d6af-105">Gets or sets the list of path IDs of the volume containers that needs to be failed-over, for which we want to fetch the eligible targets.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>