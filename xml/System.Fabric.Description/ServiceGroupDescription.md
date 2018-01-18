<Type Name="ServiceGroupDescription" FullName="System.Fabric.Description.ServiceGroupDescription">
  <TypeSignature Language="C#" Value="public sealed class ServiceGroupDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceGroupDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceGroupDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceGroupDescription" />
  <TypeSignature Language="F#" Value="type ServiceGroupDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="ef8d1-101">作成し、サービス グループを記述するために必要な情報のコレクションを提供します。</span><span class="sxs-lookup"><span data-stu-id="ef8d1-101">Provides a collection of information that is necessary to create and describe a service group.</span></span>  </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="ef8d1-102">サービス グループの説明が含まれています、<see cref="T:System.Fabric.Description.ServiceGroupDescription" />と、サービスのグループのメンバーの一覧です。</span><span class="sxs-lookup"><span data-stu-id="ef8d1-102">A service group description contains a <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> and a list of members in the service group.</span></span> <span data-ttu-id="ef8d1-103">サービスの説明は、メトリック、アプリケーション名、サービスのグループ名、およびこのサービス グループの初期化情報などの情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="ef8d1-103">The service description provides information, such as the metrics, application name, service group name, and initialization information for this service group.</span></span> <span data-ttu-id="ef8d1-104">メンバーの定義の一覧には、サービスのグループ内のサービスについて説明します。</span><span class="sxs-lookup"><span data-stu-id="ef8d1-104">The list of member definitions describes the services inside the service group.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceGroupDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceGroupDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="ef8d1-105"><see cref="T:System.Fabric.Description.ServiceGroupDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ef8d1-105">Initializes a new instance of the <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceGroupDescription (System.Fabric.Description.ServiceDescription serviceDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.Description.ServiceDescription serviceDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceGroupDescription.#ctor(System.Fabric.Description.ServiceDescription)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceGroupDescription : System.Fabric.Description.ServiceDescription -&gt; System.Fabric.Description.ServiceGroupDescription" Usage="new System.Fabric.Description.ServiceGroupDescription serviceDescription" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceDescription" Type="System.Fabric.Description.ServiceDescription" />
      </Parameters>
      <Docs>
        <param name="serviceDescription">
          <para><span data-ttu-id="ef8d1-106"><see cref="T:System.Fabric.Description.ServiceDescription" />の基礎として使用する、<see cref="T:System.Fabric.Description.ServiceGroupDescription" />です。</span><span class="sxs-lookup"><span data-stu-id="ef8d1-106">The <see cref="T:System.Fabric.Description.ServiceDescription" /> to use as the basis for the <see cref="T:System.Fabric.Description.ServiceGroupDescription" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="ef8d1-107"><see cref="T:System.Fabric.Description.ServiceGroupDescription" /> を指定して、<see cref="T:System.Fabric.Description.ServiceDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ef8d1-107">Initializes a new instance of the <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> class with the specified <see cref="T:System.Fabric.Description.ServiceDescription" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MemberDescriptions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceGroupMemberDescription&gt; MemberDescriptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ServiceGroupMemberDescription&gt; MemberDescriptions" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupDescription.MemberDescriptions" />
      <MemberSignature Language="VB.NET" Value="Public Property MemberDescriptions As IList(Of ServiceGroupMemberDescription)" />
      <MemberSignature Language="F#" Value="member this.MemberDescriptions : System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceGroupMemberDescription&gt; with get, set" Usage="System.Fabric.Description.ServiceGroupDescription.MemberDescriptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceGroupMemberDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ef8d1-108">リストを示す<see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" />このサービス グループのメンバーのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ef8d1-108">Specifies the list of <see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" /> objects for the members of this service group.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ef8d1-109">返します<see cref="T:System.Collections.Generic.IList`1" />型の<see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" />します。</span><span class="sxs-lookup"><span data-stu-id="ef8d1-109">Returns <see cref="T:System.Collections.Generic.IList`1" /> of type <see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceDescription">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ServiceDescription ServiceDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.ServiceDescription ServiceDescription" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupDescription.ServiceDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceDescription As ServiceDescription" />
      <MemberSignature Language="F#" Value="member this.ServiceDescription : System.Fabric.Description.ServiceDescription with get, set" Usage="System.Fabric.Description.ServiceGroupDescription.ServiceDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ef8d1-110">サービス グループのサービスについて説明します。</span><span class="sxs-lookup"><span data-stu-id="ef8d1-110">Describes the service group’s service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ef8d1-111"><see cref="T:System.Fabric.Description.ServiceDescription" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="ef8d1-111">Returns <see cref="T:System.Fabric.Description.ServiceDescription" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="ef8d1-112">サービスの説明では、システムで、キー、キーの範囲およびその他のプロパティなど、パーティション スキームを含む、サービス グループをパーティション分割方法について説明します。</span><span class="sxs-lookup"><span data-stu-id="ef8d1-112">The service description describes how the system should partition the service group, including the partitioning scheme, such as the key, the key range and other properties.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>