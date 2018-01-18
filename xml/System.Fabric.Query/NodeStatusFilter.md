<Type Name="NodeStatusFilter" FullName="System.Fabric.Query.NodeStatusFilter">
  <TypeSignature Language="C#" Value="public enum NodeStatusFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed NodeStatusFilter extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.NodeStatusFilter" />
  <TypeSignature Language="VB.NET" Value="Public Enum NodeStatusFilter" />
  <TypeSignature Language="F#" Value="type NodeStatusFilter = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Flags</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="df9d6-101">クエリによって返されるノードのノードの状態のマッチングに使用するフィルターを列挙します。</span><span class="sxs-lookup"><span data-stu-id="df9d6-101">Enumerates the filters used for matching the node status for nodes that should be returned by query.</span></span>
            </summary>
    <remarks><span data-ttu-id="df9d6-102">この列挙体には、<see cref="T:System.FlagsAttribute" />そのメンバーのビットごとの組み合わせをできるようにします。</span><span class="sxs-lookup"><span data-stu-id="df9d6-102">This enumeration has a <see cref="T:System.FlagsAttribute" /> that allows a bitwise combination of its members.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="All">
      <MemberSignature Language="C#" Value="All" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.NodeStatusFilter All = int32(65535)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.NodeStatusFilter.All" />
      <MemberSignature Language="VB.NET" Value="All" />
      <MemberSignature Language="F#" Value="All = 65535" Usage="System.Fabric.Query.NodeStatusFilter.All" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.NodeStatusFilter</ReturnType>
      </ReturnValue>
      <MemberValue>65535</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="df9d6-103">すべてのノードを返します。</span><span class="sxs-lookup"><span data-stu-id="df9d6-103">Returns all nodes.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="Default" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.NodeStatusFilter Default = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.NodeStatusFilter.Default" />
      <MemberSignature Language="VB.NET" Value="Default" />
      <MemberSignature Language="F#" Value="Default = 0" Usage="System.Fabric.Query.NodeStatusFilter.Default" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.NodeStatusFilter</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="df9d6-104">返しますのすべてのノード以外の不明なし、削除されました。</span><span class="sxs-lookup"><span data-stu-id="df9d6-104">Returns all nodes other than unknown and removed.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Disabled">
      <MemberSignature Language="C#" Value="Disabled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.NodeStatusFilter Disabled = int32(16)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.NodeStatusFilter.Disabled" />
      <MemberSignature Language="VB.NET" Value="Disabled" />
      <MemberSignature Language="F#" Value="Disabled = 16" Usage="System.Fabric.Query.NodeStatusFilter.Disabled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.NodeStatusFilter</ReturnType>
      </ReturnValue>
      <MemberValue>16</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="df9d6-105">無効になっているすべてのノードを返します。</span><span class="sxs-lookup"><span data-stu-id="df9d6-105">Returns all disabled nodes.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Disabling">
      <MemberSignature Language="C#" Value="Disabling" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.NodeStatusFilter Disabling = int32(8)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.NodeStatusFilter.Disabling" />
      <MemberSignature Language="VB.NET" Value="Disabling" />
      <MemberSignature Language="F#" Value="Disabling = 8" Usage="System.Fabric.Query.NodeStatusFilter.Disabling" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.NodeStatusFilter</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="df9d6-106">現在無効にするとすべてのノードを返します。</span><span class="sxs-lookup"><span data-stu-id="df9d6-106">Returns all nodes that are currently disabling.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Down">
      <MemberSignature Language="C#" Value="Down" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.NodeStatusFilter Down = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.NodeStatusFilter.Down" />
      <MemberSignature Language="VB.NET" Value="Down" />
      <MemberSignature Language="F#" Value="Down = 2" Usage="System.Fabric.Query.NodeStatusFilter.Down" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.NodeStatusFilter</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="df9d6-107">ノードをすべて返します。</span><span class="sxs-lookup"><span data-stu-id="df9d6-107">Returns all down nodes.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Enabling">
      <MemberSignature Language="C#" Value="Enabling" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.NodeStatusFilter Enabling = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.NodeStatusFilter.Enabling" />
      <MemberSignature Language="VB.NET" Value="Enabling" />
      <MemberSignature Language="F#" Value="Enabling = 4" Usage="System.Fabric.Query.NodeStatusFilter.Enabling" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.NodeStatusFilter</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="df9d6-108">現在有効にするとすべてのノードを返します。</span><span class="sxs-lookup"><span data-stu-id="df9d6-108">Returns all nodes that are currently enabling.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Removed">
      <MemberSignature Language="C#" Value="Removed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.NodeStatusFilter Removed = int32(64)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.NodeStatusFilter.Removed" />
      <MemberSignature Language="VB.NET" Value="Removed" />
      <MemberSignature Language="F#" Value="Removed = 64" Usage="System.Fabric.Query.NodeStatusFilter.Removed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.NodeStatusFilter</ReturnType>
      </ReturnValue>
      <MemberValue>64</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="df9d6-109">削除されたすべてのノードを返します。</span><span class="sxs-lookup"><span data-stu-id="df9d6-109">Returns all removed nodes.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Unknown">
      <MemberSignature Language="C#" Value="Unknown" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.NodeStatusFilter Unknown = int32(32)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.NodeStatusFilter.Unknown" />
      <MemberSignature Language="VB.NET" Value="Unknown" />
      <MemberSignature Language="F#" Value="Unknown = 32" Usage="System.Fabric.Query.NodeStatusFilter.Unknown" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.NodeStatusFilter</ReturnType>
      </ReturnValue>
      <MemberValue>32</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="df9d6-110">不明な状態にあるすべてのノードを返します。</span><span class="sxs-lookup"><span data-stu-id="df9d6-110">Returns all nodes that are in Unknown state.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Up">
      <MemberSignature Language="C#" Value="Up" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.NodeStatusFilter Up = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.NodeStatusFilter.Up" />
      <MemberSignature Language="VB.NET" Value="Up" />
      <MemberSignature Language="F#" Value="Up = 1" Usage="System.Fabric.Query.NodeStatusFilter.Up" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.NodeStatusFilter</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="df9d6-111">ノードをすべて返します。</span><span class="sxs-lookup"><span data-stu-id="df9d6-111">Returns all up nodes.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>