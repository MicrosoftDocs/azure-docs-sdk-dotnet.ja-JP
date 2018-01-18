<Type Name="Aggregate" FullName="Microsoft.Azure.Management.DataFactories.Models.Aggregate">
  <TypeSignature Language="C#" Value="public class Aggregate" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Aggregate extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.Aggregate" />
  <TypeSignature Language="VB.NET" Value="Public Class Aggregate" />
  <TypeSignature Language="F#" Value="type Aggregate = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b0468-101">その数の値と集計のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b0468-101">The aggregated parameter with the count value for it.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Aggregate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.Aggregate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b0468-102">集計のクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b0468-102">Initializes a new instance of the Aggregate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Aggregate (long count, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 count, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.Aggregate.#ctor(System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (count As Long, value As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.Aggregate : int64 * string -&gt; Microsoft.Azure.Management.DataFactories.Models.Aggregate" Usage="new Microsoft.Azure.Management.DataFactories.Models.Aggregate (count, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="count" Type="System.Int64" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="count">To be added.</param>
        <param name="value">To be added.</param>
        <summary>
            <span data-ttu-id="b0468-103">必須の引数で、集計クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b0468-103">Initializes a new instance of the Aggregate class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public long Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.Aggregate.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Long" />
      <MemberSignature Language="F#" Value="member this.Count : int64 with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.Aggregate.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b0468-104">必須。</span><span class="sxs-lookup"><span data-stu-id="b0468-104">Required.</span></span> <span data-ttu-id="b0468-105">集計された値。</span><span class="sxs-lookup"><span data-stu-id="b0468-105">The aggregated value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.Aggregate.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.Aggregate.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b0468-106">必須。</span><span class="sxs-lookup"><span data-stu-id="b0468-106">Required.</span></span> <span data-ttu-id="b0468-107">集計 count が属するアクティビティ ウィンドウ パラメーターの値。</span><span class="sxs-lookup"><span data-stu-id="b0468-107">The activity window parameter's value that the aggregate count belongs to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>