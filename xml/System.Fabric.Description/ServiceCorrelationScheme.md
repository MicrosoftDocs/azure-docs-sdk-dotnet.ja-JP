<Type Name="ServiceCorrelationScheme" FullName="System.Fabric.Description.ServiceCorrelationScheme">
  <TypeSignature Language="C#" Value="public enum ServiceCorrelationScheme" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServiceCorrelationScheme extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceCorrelationScheme" />
  <TypeSignature Language="VB.NET" Value="Public Enum ServiceCorrelationScheme" />
  <TypeSignature Language="F#" Value="type ServiceCorrelationScheme = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="a417a-101">このサービスが別のサービスに関連付けられていて、そのサービスとの関係について説明することを示します。</span><span class="sxs-lookup"><span data-stu-id="a417a-101">Indicates that this service is associated with another service, and describes the relationship with that service.</span></span></para>
    </summary>
    <remarks>
      <para />
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Affinity">
      <MemberSignature Language="C#" Value="Affinity" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServiceCorrelationScheme Affinity = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServiceCorrelationScheme.Affinity" />
      <MemberSignature Language="VB.NET" Value="Affinity" />
      <MemberSignature Language="F#" Value="Affinity = 1" Usage="System.Fabric.Description.ServiceCorrelationScheme.Affinity" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceCorrelationScheme</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a417a-102">このサービスが別のサービスとのアフィニティの関係を持つことを示します。</span><span class="sxs-lookup"><span data-stu-id="a417a-102">Indicates that this service has an affinity relationship with another service.</span></span> <span data-ttu-id="a417a-103">旧バージョンとの互換性のため、提供、Aligned または NonAlignedAffinity オプションを使い続ける理由を検討してください。</span><span class="sxs-lookup"><span data-stu-id="a417a-103">Provided for backwards compatibility, consider preferring the Aligned or NonAlignedAffinity options.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="AlignedAffinity">
      <MemberSignature Language="C#" Value="AlignedAffinity" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServiceCorrelationScheme AlignedAffinity = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServiceCorrelationScheme.AlignedAffinity" />
      <MemberSignature Language="VB.NET" Value="AlignedAffinity" />
      <MemberSignature Language="F#" Value="AlignedAffinity = 2" Usage="System.Fabric.Description.ServiceCorrelationScheme.AlignedAffinity" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceCorrelationScheme</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a417a-104">アラインされたアフィニティによって、同じノードでアフィニティを設定したサービスのパーティションのプライマリが併置されています。</span><span class="sxs-lookup"><span data-stu-id="a417a-104">Aligned affinity ensures that the primaries of the partitions of the affinitized services are collocated on the same nodes.</span></span> <span data-ttu-id="a417a-105">これは、既定値は、「アフィニティ」スキームを選択すると同じです。</span><span class="sxs-lookup"><span data-stu-id="a417a-105">This is the default and is the same as selecting the “Affinity” scheme.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServiceCorrelationScheme Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServiceCorrelationScheme.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Description.ServiceCorrelationScheme.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceCorrelationScheme</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a417a-106">無効な相関関係スキームの場合。</span><span class="sxs-lookup"><span data-stu-id="a417a-106">An invalid correlation scheme.</span></span> <span data-ttu-id="a417a-107">使用できません。</span><span class="sxs-lookup"><span data-stu-id="a417a-107">Cannot be used.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="NonAlignedAffinity">
      <MemberSignature Language="C#" Value="NonAlignedAffinity" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServiceCorrelationScheme NonAlignedAffinity = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServiceCorrelationScheme.NonAlignedAffinity" />
      <MemberSignature Language="VB.NET" Value="NonAlignedAffinity" />
      <MemberSignature Language="F#" Value="NonAlignedAffinity = 3" Usage="System.Fabric.Description.ServiceCorrelationScheme.NonAlignedAffinity" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceCorrelationScheme</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="a417a-108">非固定アフィニティでは、各サービスのすべてのレプリカが同じノード上に配置することを保証します。</span><span class="sxs-lookup"><span data-stu-id="a417a-108">Non-Aligned affinity guarantees that all replicas of each service will be placed on the same nodes.</span></span> <span data-ttu-id="a417a-109">配置のアフィニティとは異なりこれは保証されません特定のロールのレプリカを併置することです。</span><span class="sxs-lookup"><span data-stu-id="a417a-109">Unlike Aligned Affinity, this does not guarantee that replicas of particular role will be collocated.</span></span> </para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>