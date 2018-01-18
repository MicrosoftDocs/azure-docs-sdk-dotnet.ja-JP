<Type Name="IWithSku" FullName="Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithSku">
  <TypeSignature Language="C#" Value="public interface IWithSku" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSku" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithSku" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSku" />
  <TypeSignature Language="F#" Value="type IWithSku = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ee1c3-101">パラメーターを変更できるように、Redis Cache 更新の段階です。</span><span class="sxs-lookup"><span data-stu-id="ee1c3-101">A Redis Cache update stage allowing to change the parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithBasicSku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithBasicSku (int capacity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithBasicSku(int32 capacity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithSku.WithBasicSku(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithBasicSku (capacity As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithBasicSku : int -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iWithSku.WithBasicSku capacity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="capacity" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="capacity"><span data-ttu-id="ee1c3-102">Basic sku の C ファミリ (0、1、2、3、4、5、6) で更新する Redis キャッシュのサイズを指定します。</span><span class="sxs-lookup"><span data-stu-id="ee1c3-102">Specifies what size of Redis Cache to update to for Basic sku with C family (0, 1, 2, 3, 4, 5, 6).</span></span></param>
        <summary>
            <span data-ttu-id="ee1c3-103">新しい容量で基本的な sku に Redis Cache を更新します。</span><span class="sxs-lookup"><span data-stu-id="ee1c3-103">Updates Redis Cache to Basic sku with new capacity.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ee1c3-104">Redis キャッシュの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ee1c3-104">The next stage of Redis Cache update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPremiumSku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithPremiumSku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithPremiumSku() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithSku.WithPremiumSku" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPremiumSku () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPremiumSku : unit -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iWithSku.WithPremiumSku " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ee1c3-105">Premium sku に Redis Cache を更新します。</span><span class="sxs-lookup"><span data-stu-id="ee1c3-105">Updates Redis Cache to Premium sku.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ee1c3-106">Redis キャッシュの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ee1c3-106">The next stage of Redis Cache update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPremiumSku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithPremiumSku (int capacity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithPremiumSku(int32 capacity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithSku.WithPremiumSku(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPremiumSku (capacity As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPremiumSku : int -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iWithSku.WithPremiumSku capacity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="capacity" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="capacity"><span data-ttu-id="ee1c3-107">Premium sku の P ファミリ (1、2、3、4) で更新する Redis キャッシュのサイズを指定します。</span><span class="sxs-lookup"><span data-stu-id="ee1c3-107">Specifies what size of Redis Cache to update to for Premium sku with P family (1, 2, 3, 4).</span></span></param>
        <summary>
            <span data-ttu-id="ee1c3-108">新しい容量を持つ Premium sku に Redis Cache を更新します。</span><span class="sxs-lookup"><span data-stu-id="ee1c3-108">Updates Redis Cache to Premium sku with new capacity.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ee1c3-109">Redis キャッシュの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ee1c3-109">The next stage of Redis Cache update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithStandardSku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithStandardSku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithStandardSku() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithSku.WithStandardSku" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStandardSku () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithStandardSku : unit -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iWithSku.WithStandardSku " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ee1c3-110">標準の sku に Redis Cache を更新します。</span><span class="sxs-lookup"><span data-stu-id="ee1c3-110">Updates Redis Cache to Standard sku.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ee1c3-111">Redis キャッシュの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ee1c3-111">The next stage of Redis Cache update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithStandardSku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithStandardSku (int capacity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithStandardSku(int32 capacity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithSku.WithStandardSku(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStandardSku (capacity As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithStandardSku : int -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iWithSku.WithStandardSku capacity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="capacity" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="capacity"><span data-ttu-id="ee1c3-112">C ファミリ (0、1、2、3、4、5、6) と標準の sku に更新する Redis キャッシュのサイズを指定します。</span><span class="sxs-lookup"><span data-stu-id="ee1c3-112">Specifies what size of Redis Cache to update to for Standard sku with C family (0, 1, 2, 3, 4, 5, 6).</span></span></param>
        <summary>
            <span data-ttu-id="ee1c3-113">新しい容量を持つ、標準の sku に Redis Cache を更新します。</span><span class="sxs-lookup"><span data-stu-id="ee1c3-113">Updates Redis Cache to Standard sku with new capacity.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ee1c3-114">Redis キャッシュの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="ee1c3-114">The next stage of Redis Cache update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>