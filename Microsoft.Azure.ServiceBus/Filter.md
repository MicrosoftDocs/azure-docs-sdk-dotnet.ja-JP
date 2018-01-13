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
            メッセージに対して評価されるフィルター式をについて説明します。
            </summary>
    <remarks>
            フィルターは、次の具体的な実装を持つ抽象クラス: <list type="bullet"> <item> <b>SqlFilter</b>を表す SQL 構文を使用してフィルターします。</item><item><b>CorrelationFilter</b>等価式相関関係の最適化を提供します。</item></list></remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.SqlFilter" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.TrueFilter" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.CorrelationFilter" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.FalseFilter" />
  </Docs>
  <Members />
</Type>