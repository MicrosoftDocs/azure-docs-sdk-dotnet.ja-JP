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
            パラメーターを変更できるように、Redis Cache 更新の段階です。
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
        <param name="capacity">Basic sku の C ファミリ (0、1、2、3、4、5、6) で更新する Redis キャッシュのサイズを指定します。</param>
        <summary>
            新しい容量で基本的な sku に Redis Cache を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Redis キャッシュの更新の次のステージ。</return>
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
            Premium sku に Redis Cache を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Redis キャッシュの更新の次のステージ。</return>
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
        <param name="capacity">Premium sku の P ファミリ (1、2、3、4) で更新する Redis キャッシュのサイズを指定します。</param>
        <summary>
            新しい容量を持つ Premium sku に Redis Cache を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Redis キャッシュの更新の次のステージ。</return>
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
            標準の sku に Redis Cache を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Redis キャッシュの更新の次のステージ。</return>
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
        <param name="capacity">C ファミリ (0、1、2、3、4、5、6) と標準の sku に更新する Redis キャッシュのサイズを指定します。</param>
        <summary>
            新しい容量を持つ、標準の sku に Redis Cache を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Redis キャッシュの更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>