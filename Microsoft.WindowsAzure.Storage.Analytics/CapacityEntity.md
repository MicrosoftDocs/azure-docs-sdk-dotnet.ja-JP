<Type Name="CapacityEntity" FullName="Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity">
  <TypeSignature Language="C#" Value="public class CapacityEntity : Microsoft.WindowsAzure.Storage.Table.TableEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CapacityEntity extends Microsoft.WindowsAzure.Storage.Table.TableEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity" />
  <TypeSignature Language="VB.NET" Value="Public Class CapacityEntity&#xA;Inherits TableEntity" />
  <TypeSignature Language="F#" Value="type CapacityEntity = class&#xA;    inherit TableEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Table.TableEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Storage analytics 容量テーブル内のエンティティを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CapacityEntity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public long Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As Long" />
      <MemberSignature Language="F#" Value="member this.Capacity : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または容量エンティティには、ストレージ アカウントで使用される Blob ストレージの量を示す Capacity プロパティを設定します。
            </summary>
        <value>この容量エンティティごとのストレージ アカウントによって使用される Blob ストレージの数量を表す long 値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerCount">
      <MemberSignature Language="C#" Value="public long ContainerCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ContainerCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity.ContainerCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerCount As Long" />
      <MemberSignature Language="F#" Value="member this.ContainerCount : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity.ContainerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または容量エンティティには、ストレージ アカウント内の blob コンテナーの数を示す ContainerCount プロパティを設定します。
            </summary>
        <value>この容量エンティティごとのストレージ アカウント内の blob コンテナーの数を表す long 値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectCount">
      <MemberSignature Language="C#" Value="public long ObjectCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ObjectCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity.ObjectCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ObjectCount As Long" />
      <MemberSignature Language="F#" Value="member this.ObjectCount : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity.ObjectCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または容量エンティティには、ストレージ アカウント内のコミット済みおよびコミット前の blob の数を示す ObjectCount プロパティを設定します。
            </summary>
        <value>この容量エンティティごとのストレージ アカウント内のコミット済みおよびコミット前の blob の数を表す long 値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Time">
      <MemberSignature Language="C#" Value="public DateTimeOffset Time { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Time" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity.Time" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Time As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Time : DateTimeOffset" Usage="Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity.Time" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            (Utc)、そのログ エントリの開始時刻を表す容量エンティティのタイムスタンプを取得します。
            </summary>
        <value>UTC のタイムスタンプを含む文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>