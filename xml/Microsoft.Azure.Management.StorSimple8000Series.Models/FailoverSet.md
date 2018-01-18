<Type Name="FailoverSet" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet">
  <TypeSignature Language="C#" Value="public class FailoverSet" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FailoverSet extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet" />
  <TypeSignature Language="VB.NET" Value="Public Class FailoverSet" />
  <TypeSignature Language="F#" Value="type FailoverSet = class" />
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
            <span data-ttu-id="29b80-101">デバイスの設定のフェイル オーバーします。</span><span class="sxs-lookup"><span data-stu-id="29b80-101">The failover set on a device.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverSet ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="29b80-102">FailoverSet クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="29b80-102">Initializes a new instance of the FailoverSet class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverSet (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainerFailoverMetadata&gt; volumeContainers = null, Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSetEligibilityResult eligibilityResult = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainerFailoverMetadata&gt; volumeContainers, class Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSetEligibilityResult eligibilityResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainerFailoverMetadata},Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSetEligibilityResult)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional volumeContainers As IList(Of VolumeContainerFailoverMetadata) = null, Optional eligibilityResult As FailoverSetEligibilityResult = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainerFailoverMetadata&gt; * Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSetEligibilityResult -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet (volumeContainers, eligibilityResult)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="volumeContainers" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainerFailoverMetadata&gt;" />
        <Parameter Name="eligibilityResult" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSetEligibilityResult" />
      </Parameters>
      <Docs>
        <param name="volumeContainers"><span data-ttu-id="29b80-103">フェールオーバーの一部のボリューム コンテナーのメタデータの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="29b80-103">The list of meta data of volume containers, which are part of the failover set.</span></span></param>
        <param name="eligibilityResult"><span data-ttu-id="29b80-104">フェールオーバーの対象となる結果は、フェールオーバーの設定。</span><span class="sxs-lookup"><span data-stu-id="29b80-104">The eligibility result of the failover set, for failover.</span></span></param>
        <summary>
            <span data-ttu-id="29b80-105">FailoverSet クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="29b80-105">Initializes a new instance of the FailoverSet class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EligibilityResult">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSetEligibilityResult EligibilityResult { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSetEligibilityResult EligibilityResult" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet.EligibilityResult" />
      <MemberSignature Language="VB.NET" Value="Public Property EligibilityResult As FailoverSetEligibilityResult" />
      <MemberSignature Language="F#" Value="member this.EligibilityResult : Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSetEligibilityResult with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet.EligibilityResult" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eligibilityResult")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSetEligibilityResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b80-106">取得またはフェールオーバー用のフェールオーバー セットの対象となる結果を設定します。</span><span class="sxs-lookup"><span data-stu-id="29b80-106">Gets or sets the eligibility result of the failover set, for failover.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeContainers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainerFailoverMetadata&gt; VolumeContainers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainerFailoverMetadata&gt; VolumeContainers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet.VolumeContainers" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeContainers As IList(Of VolumeContainerFailoverMetadata)" />
      <MemberSignature Language="F#" Value="member this.VolumeContainers : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainerFailoverMetadata&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet.VolumeContainers" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainerFailoverMetadata&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b80-107">取得またはフェールオーバー セットの一部のボリューム コンテナーのメタデータの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="29b80-107">Gets or sets the list of meta data of volume containers, which are part of the failover set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>