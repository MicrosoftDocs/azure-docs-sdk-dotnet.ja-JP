<Type Name="Filter" FullName="Microsoft.Azure.ServiceBus.Filter">
  <TypeSignature Language="C#" Value="public abstract class Filter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Filter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Filter" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Filter" />
  <TypeSignature Language="F#" Value="type Filter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="59387-101">メッセージに対して評価されるフィルター式をについて説明します。</span><span class="sxs-lookup"><span data-stu-id="59387-101">Describes a filter expression that is evaluated against a Message.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="59387-102">フィルターは、次の具体的な実装を持つ抽象クラス: <list type="bullet"> <item> <b>SqlFilter</b>を表す SQL 構文を使用してフィルターします。</item><item><b>CorrelationFilter</b>等価式相関関係の最適化を提供します。</item></list></span><span class="sxs-lookup"><span data-stu-id="59387-102">Filter is an abstract class with the following concrete implementations: <list type="bullet"><item><b>SqlFilter</b> that represents a filter using SQL syntax. </item><item><b>CorrelationFilter</b> that provides an optimization for correlation equality expressions.</item></list></span></span></remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.SqlFilter" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.TrueFilter" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.CorrelationFilter" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.FalseFilter" />
  </Docs>
  <Members />
</Type>