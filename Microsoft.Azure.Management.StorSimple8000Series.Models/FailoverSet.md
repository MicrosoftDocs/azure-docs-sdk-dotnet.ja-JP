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
            デバイスの設定のフェイル オーバーします。
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
            FailoverSet クラスの新しいインスタンスを初期化します。
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
        <param name="volumeContainers">フェールオーバーの一部のボリューム コンテナーのメタデータの一覧を設定します。</param>
        <param name="eligibilityResult">フェールオーバーの対象となる結果は、フェールオーバーの設定。</param>
        <summary>
            FailoverSet クラスの新しいインスタンスを初期化します。
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
            取得またはフェールオーバー用のフェールオーバー セットの対象となる結果を設定します。
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
            取得またはフェールオーバー セットの一部のボリューム コンテナーのメタデータの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>