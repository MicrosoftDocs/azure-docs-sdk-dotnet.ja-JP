<Type Name="PropertyEnumerationResult" FullName="System.Fabric.PropertyEnumerationResult">
  <TypeSignature Language="C#" Value="public class PropertyEnumerationResult : System.Collections.ObjectModel.Collection&lt;System.Fabric.NamedProperty&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PropertyEnumerationResult extends System.Collections.ObjectModel.Collection`1&lt;class System.Fabric.NamedProperty&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PropertyEnumerationResult" />
  <TypeSignature Language="VB.NET" Value="Public Class PropertyEnumerationResult&#xA;Inherits Collection(Of NamedProperty)" />
  <TypeSignature Language="F#" Value="type PropertyEnumerationResult = class&#xA;    inherit Collection&lt;NamedProperty&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Collections.ObjectModel.Collection&lt;System.Fabric.NamedProperty&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">System.Fabric.NamedProperty</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="fe349-101">プロパティ マネージャーによって、操作から返されるプロパティの列挙を表します。</span><span class="sxs-lookup"><span data-stu-id="fe349-101">Represents an enumeration of properties that is returned from an operation by the property manager.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HasMoreData">
      <MemberSignature Language="C#" Value="public bool HasMoreData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasMoreData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyEnumerationResult.HasMoreData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasMoreData As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasMoreData : bool" Usage="System.Fabric.PropertyEnumerationResult.HasMoreData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="fe349-102">複数の残りのページがあることを示します。</span><span class="sxs-lookup"><span data-stu-id="fe349-102">Indicates that there are more remaining pages.</span></span> 
            <span data-ttu-id="fe349-103"><see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult,System.TimeSpan,System.Threading.CancellationToken)" />次のページの取得を呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="fe349-103"><see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult,System.TimeSpan,System.Threading.CancellationToken)" /> should be called to get the next page.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="fe349-104"><see cref="T:System.Boolean" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="fe349-104">Returns <see cref="T:System.Boolean" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBestEffort">
      <MemberSignature Language="C#" Value="public bool IsBestEffort { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBestEffort" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyEnumerationResult.IsBestEffort" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsBestEffort As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBestEffort : bool" Usage="System.Fabric.PropertyEnumerationResult.IsBestEffort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="fe349-105">指定した名前で名前が、列挙中に変更されたかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="fe349-105">Indicates whether the name under the given name has been modified during the enumeration.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="fe349-106"><see cref="T:System.Boolean" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="fe349-106">Returns <see cref="T:System.Boolean" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="fe349-107">変更があった場合は、このプロパティは true です。</span><span class="sxs-lookup"><span data-stu-id="fe349-107">If there was a modification, this property is true.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="IsConsistent">
      <MemberSignature Language="C#" Value="public bool IsConsistent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsConsistent" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyEnumerationResult.IsConsistent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsConsistent As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsConsistent : bool" Usage="System.Fabric.PropertyEnumerationResult.IsConsistent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="fe349-108">指定した名前で、名前が、列挙中に変更されたかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="fe349-108">Indicates whether the any name under the given name has been modified during the enumeration.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="fe349-109"><see cref="T:System.Boolean" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="fe349-109">Returns <see cref="T:System.Boolean" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="fe349-110">変更があった場合は、このプロパティは false です。</span><span class="sxs-lookup"><span data-stu-id="fe349-110">If there was a modification, this property is false.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="IsFinished">
      <MemberSignature Language="C#" Value="public bool IsFinished { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsFinished" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyEnumerationResult.IsFinished" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsFinished As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsFinished : bool" Usage="System.Fabric.PropertyEnumerationResult.IsFinished" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="fe349-111">これ以上の残りのページがあることを示します。</span><span class="sxs-lookup"><span data-stu-id="fe349-111">Indicates that there are no more remaining pages.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="fe349-112"><see cref="T:System.Boolean" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="fe349-112">Returns <see cref="T:System.Boolean" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsValid">
      <MemberSignature Language="C#" Value="public bool IsValid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsValid" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyEnumerationResult.IsValid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsValid As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsValid : bool" Usage="System.Fabric.PropertyEnumerationResult.IsValid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="fe349-113">列挙結果が有効かどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="fe349-113">Indicates whether the enumeration result is valid.</span></span> <span data-ttu-id="fe349-114">有効でない場合、結果を使用しません。</span><span class="sxs-lookup"><span data-stu-id="fe349-114">Do not use the result if it is not valid.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="fe349-115"><see cref="T:System.Boolean" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="fe349-115">Returns <see cref="T:System.Boolean" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>